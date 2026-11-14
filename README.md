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

## Species ID (release `models-v2`)

Downloaded when the user turns on wildlife species ID; verified by SHA-256 before use.

| File | Size | SHA-256 |
| --- | --- | --- |
| `bioclip2-visual-q8.onnx` (image encoder) | 306,306,716 bytes | `d70729762a0ecd6140508bb998f84dc0a1c43a96a26e5f45d095a1574ccbcfc8` |
| `bioclip2-species.bin` (species list) | 30,416,966 bytes | `7e65df6b9c524a9cd3a8e34945e73dec7d161c70048cafc1c25a63d36b9974ee` |

BioCLIP 2 (https://huggingface.co/imageomics/bioclip-2): © Imageomics Institute, MIT License. Converted to ONNX
with 8-bit weights; no other changes. Gu, J. et al., "BioCLIP 2: Emergent Properties from Scaling Hierarchical
Contrastive Learning", 2025.

Species list: BioCLIP 2 text embeddings of the TreeOfLife-200M taxonomy (https://huggingface.co/datasets/imageomics/TreeOfLife-200M,
compilation CC0 1.0), reduced to birds, mammals, reptiles, amphibians, butterflies/moths and dragonflies that have a common
name, stored with 8-bit precision. Common names: GBIF Backbone Taxonomy, VernacularName component, CC BY 4.0,
GBIF Secretariat, https://doi.org/10.15468/39omei
