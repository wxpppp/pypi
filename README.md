# 🏗️ LoongArch Python Package Build CI

[简体中文](./README_zh.md)

This repository automatically builds and maintains **Python (pip) packages** for the **LoongArch (loongarch64)** architecture.

---

## 📦 Supported Build Workflows

| No. | Package | Workflow |
|-----|----------|-----------|
| 1 | MarkupSafe | [MarkupSafe.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/MarkupSafe.yaml) |
| 2 | PyYAML | [PyYAML.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/PyYAML.yaml) |
| 3 | SQLAlchemy | [SQLAlchemy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/SQLAlchemy.yaml) |
| 4 | aiohttp | [aiohttp.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/aiohttp.yaml) |
| 5 | apache-tvm | [apache-tvm.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/apache-tvm.yaml) |
| 6 | cadquery-vtk | [cadquery-vtk.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cadquery-vtk.yaml) |
| 7 | cffi | [cffi.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cffi.yaml) |
| 8 | charset-normalizer | [charset-normalizer.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/charset-normalizer.yaml) |
| 9 | cibuildwheel | [cibuildwheel.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cibuildwheel.yaml) |
| 10 | cmake | [cmake.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cmake.yaml) |
| 11 | contourpy | [contourpy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/contourpy.yaml) |
| 12 | crc32c | [crc32c.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/crc32c.yaml) |
| 13 | cryptography | [cryptography.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cryptography.yaml) |
| 14 | ctranslate2 | [ctranslate2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ctranslate2.yaml) |
| 15 | cymem | [cymem.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cymem.yaml) |
| 16 | faiss-cpu | [faiss-cpu.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/faiss-cpu.yaml) |
| 17 | gevent | [gevent.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/gevent.yaml) |
| 18 | greenlet | [greenlet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/greenlet.yaml) |
| 19 | grpcio-tools | [grpcio-tools.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio-tools.yaml) |
| 20 | grpcio | [grpcio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio.yaml) |
| 21 | h5py | [h5py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/h5py.yaml) |
| 22 | hf-xet | [hf-xet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/hf-xet.yaml) |
| 23 | jiter | [jiter.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/jiter.yaml) |
| 24 | kiwisolver | [kiwisolver.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kiwisolver.yaml) |
| 25 | kornia-rs | [kornia-rs.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kornia-rs.yaml) |
| 26 | lintrunner | [lintrunner.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lintrunner.yaml) |
| 27 | llama-cpp-python | [llama-cpp-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llama-cpp-python.yaml) |
| 28 | llguidance | [llguidance.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llguidance.yaml) |
| 29 | llvmlite | [llvmlite.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llvmlite.yaml) |
| 30 | lxml | [lxml.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lxml.yaml) |
| 31 | matplotlib | [matplotlib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/matplotlib.yaml) |
| 32 | maturin | [maturin.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/maturin.yaml) |
| 33 | ml_dtypes | [ml_dtypes.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ml_dtypes.yaml) |
| 34 | msgpack | [msgpack.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/msgpack.yaml) |
| 35 | nh3 | [nh3.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nh3.yaml) |
| 36 | ninja | [ninja.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ninja.yaml) |
| 37 | nlopt | [nlopt.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nlopt.yaml) |
| 38 | numba | [numba.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numba.yaml) |
| 39 | numpy | [numpy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numpy.yaml) |
| 40 | onnx | [onnx.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnx.yaml) |
| 41 | onnxruntime | [onnxruntime.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnxruntime.yaml) |
| 42 | opencv-contrib-python | [opencv-contrib-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-contrib-python.yaml) |
| 43 | opencv-python-headless | [opencv-python-headless.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-headless.yaml) |
| 44 | opencv-python | [opencv-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python.yaml) |
| 45 | optree | [optree.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/optree.yaml) |
| 46 | orjson | [orjson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/orjson.yaml) |
| 47 | pandas | [pandas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pandas.yaml) |
| 48 | patchelf | [patchelf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/patchelf.yaml) |
| 49 | pillow | [pillow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pillow.yaml) |
| 50 | preshed | [preshed.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/preshed.yaml) |
| 51 | psycopg-binary | [psycopg-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg-binary.yaml) |
| 52 | psycopg2-binary | [psycopg2-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg2-binary.yaml) |
| 53 | pyarrow | [pyarrow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pyarrow.yaml) |
| 54 | pydantic-core | [pydantic-core.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pydantic-core.yaml) |
| 55 | pygit2 | [pygit2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pygit2.yaml) |
| 56 | pymupdf | [pymupdf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pymupdf.yaml) |
| 57 | regex | [regex.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/regex.yaml) |
| 58 | rpds-py | [rpds-py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/rpds-py.yaml) |
| 59 | ruamel-yaml-clib | [ruamel-yaml-clib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruamel-yaml-clib.yaml) |
| 60 | ruff | [ruff.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruff.yaml) |
| 61 | safetensors | [safetensors.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/safetensors.yaml) |
| 62 | scikit-learn | [scikit-learn.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scikit-learn.yaml) |
| 63 | scipy-openblas | [scipy-openblas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy-openblas.yaml) |
| 64 | scipy | [scipy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy.yaml) |
| 65 | sentencepiece | [sentencepiece.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/sentencepiece.yaml) |
| 66 | shapely | [shapely.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/shapely.yaml) |
| 67 | soundfile | [soundfile.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soundfile.yaml) |
| 68 | soxr | [soxr.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soxr.yaml) |
| 69 | spacy | [spacy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/spacy.yaml) |
| 70 | srsly | [srsly.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/srsly.yaml) |
| 71 | swig | [swig.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/swig.yaml) |
| 72 | thinc | [thinc.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/thinc.yaml) |
| 73 | tiktoken | [tiktoken.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tiktoken.yaml) |
| 74 | tokenizers | [tokenizers.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tokenizers.yaml) |
| 75 | torch | [torch.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torch.yaml) |
| 76 | torchaudio | [torchaudio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchaudio.yaml) |
| 77 | torchvision | [torchvision.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchvision.yaml) |
| 78 | ujson | [ujson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ujson.yaml) |
| 79 | uv | [uv.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/uv.yaml) |
| 80 | xxhash | [xxhash.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/xxhash.yaml) |
| 81 | zope.interface | [zope.interface.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/zope.interface.yaml) |

_This table is automatically generated by GitHub Actions._

---

## ⚙️ Automation Details

- Each package has a dedicated workflow under `.github/workflows/`.
- This workflow runs **daily** and regenerates README when workflow files change.

---

## 🕒 Last Updated

- UTC Time: `2025-10-20 05:21:00`
- Local Time (Asia/Shanghai): `2025-10-20 13:21:00`
