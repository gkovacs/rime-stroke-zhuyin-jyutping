# rime-stroke-zhuyin-jyutping

## About

This is a layout for typing in Chinese via strokes. Use `hspnz` for entering strokes. The mapping is below:

* h 一 (横)
* s 丨 (竖)
* p 丿 (撇)
* n 丶 (捺)
* z 乙 (折)

Zhuyin (注音) and Jyutping (粤拼) will be shown as you type.

## Installing

First ensure you have plum installed. For macOS this would be:

```bash
cd ~/Library/Rime
wget https://git.io/rime-install
```

Then install `gkovacs/rime-stroke-zhuyin-jyutping` using plum:

```bash
bash rime-install gkovacs/rime-stroke-zhuyin-jyutping
```

Finally edit `default.custom.yaml` and add `stroke_zhuyin_jyutping` to the schema list:

```bash
patch:
  schema_list:
    - schema: stroke_zhuyin_jyutping
```

Now reload RIME and it should appear under your layouts.
