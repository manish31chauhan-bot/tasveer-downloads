# Tasveer downloads

Public download files for **Tasveer by IARA**. No source code lives here.

## AI models (release `models-v1`)

Downloaded by Tasveer on first use (✦ Subject mask, IARA voice) and verified by SHA-256 before use.

| File | Size | SHA-256 |
| --- | --- | --- |
| `u2netp.onnx` (Fast) | 4,574,861 bytes | `309c8469258dda742793dce0ebea8e6dd393174f89934733ecc8b14c76f4ddd8` |
| `isnet-general-use.onnx` (High detail) | 178,648,008 bytes | `60920e99c45464f2ba57bee2ad08c919a52bbf852739e96947fbb4358c0d964a` |
| `ggml-base.en-q5_1.bin` (IARA voice) | 59,721,011 bytes | `4baf70dd0d7c4247ba2b81fafd9c01005ac77c2f9ef064e00dcf195d0e2fdd2f` |

U²-Net: Xuebin Qin, Zichen Zhang, Chenyang Huang, Masood Dehghan, Osmar R. Zaiane, Martin Jagersand.
ISNet / DIS: Xuebin Qin, Hang Dai, Xiaobin Hu, Deng-Ping Fan, Ling Shao, Luc Van Gool.
Licensed under the Apache License 2.0 (see `LICENSE-MODELS`).

Whisper `base.en`: © 2022 OpenAI, MIT License; quantised GGML file as published by the whisper.cpp project
(https://github.com/ggml-org/whisper.cpp), unmodified. Used by Tasveer's IARA assistant for on-device voice commands. Files are unmodified, as distributed by the
rembg project (https://github.com/danielgatis/rembg).
