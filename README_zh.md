# 🏗️ LoongArch Python 包构建自动化仓库

[English](./README.md)

本仓库用于自动构建和维护 **LoongArch（loongarch64）** 架构下的 **Python 第三方库（pip 包）**。

---

## 📦 当前支持的构建任务

| 序号 | 包名称 | Workflow 文件 |
|------|----------|----------------|
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
| 14 | cymem | [cymem.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cymem.yaml) |
| 15 | faiss-cpu | [faiss-cpu.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/faiss-cpu.yaml) |
| 16 | gevent | [gevent.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/gevent.yaml) |
| 17 | greenlet | [greenlet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/greenlet.yaml) |
| 18 | grpcio-tools | [grpcio-tools.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio-tools.yaml) |
| 19 | grpcio | [grpcio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio.yaml) |
| 20 | h5py | [h5py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/h5py.yaml) |
| 21 | hf-xet | [hf-xet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/hf-xet.yaml) |
| 22 | jiter | [jiter.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/jiter.yaml) |
| 23 | kiwisolver | [kiwisolver.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kiwisolver.yaml) |
| 24 | kornia-rs | [kornia-rs.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kornia-rs.yaml) |
| 25 | lintrunner | [lintrunner.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lintrunner.yaml) |
| 26 | llama-cpp-python | [llama-cpp-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llama-cpp-python.yaml) |
| 27 | llguidance | [llguidance.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llguidance.yaml) |
| 28 | llvmlite | [llvmlite.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llvmlite.yaml) |
| 29 | lxml | [lxml.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lxml.yaml) |
| 30 | matplotlib | [matplotlib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/matplotlib.yaml) |
| 31 | maturin | [maturin.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/maturin.yaml) |
| 32 | ml_dtypes | [ml_dtypes.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ml_dtypes.yaml) |
| 33 | msgpack | [msgpack.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/msgpack.yaml) |
| 34 | nh3 | [nh3.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nh3.yaml) |
| 35 | ninja | [ninja.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ninja.yaml) |
| 36 | nlopt | [nlopt.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nlopt.yaml) |
| 37 | numba | [numba.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numba.yaml) |
| 38 | numpy | [numpy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numpy.yaml) |
| 39 | onnx | [onnx.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnx.yaml) |
| 40 | onnxruntime | [onnxruntime.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnxruntime.yaml) |
| 41 | opencv-contrib-python | [opencv-contrib-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-contrib-python.yaml) |
| 42 | opencv-python-headless | [opencv-python-headless.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-headless.yaml) |
| 43 | opencv-python | [opencv-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python.yaml) |
| 44 | optree | [optree.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/optree.yaml) |
| 45 | orjson | [orjson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/orjson.yaml) |
| 46 | pandas | [pandas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pandas.yaml) |
| 47 | patchelf | [patchelf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/patchelf.yaml) |
| 48 | pillow | [pillow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pillow.yaml) |
| 49 | preshed | [preshed.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/preshed.yaml) |
| 50 | psycopg-binary | [psycopg-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg-binary.yaml) |
| 51 | psycopg2-binary | [psycopg2-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg2-binary.yaml) |
| 52 | pyarrow | [pyarrow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pyarrow.yaml) |
| 53 | pydantic-core | [pydantic-core.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pydantic-core.yaml) |
| 54 | pygit2 | [pygit2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pygit2.yaml) |
| 55 | pymupdf | [pymupdf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pymupdf.yaml) |
| 56 | regex | [regex.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/regex.yaml) |
| 57 | rpds-py | [rpds-py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/rpds-py.yaml) |
| 58 | ruamel-yaml-clib | [ruamel-yaml-clib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruamel-yaml-clib.yaml) |
| 59 | ruff | [ruff.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruff.yaml) |
| 60 | safetensors | [safetensors.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/safetensors.yaml) |
| 61 | scikit-learn | [scikit-learn.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scikit-learn.yaml) |
| 62 | scipy-openblas | [scipy-openblas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy-openblas.yaml) |
| 63 | scipy | [scipy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy.yaml) |
| 64 | sentencepiece | [sentencepiece.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/sentencepiece.yaml) |
| 65 | shapely | [shapely.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/shapely.yaml) |
| 66 | soundfile | [soundfile.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soundfile.yaml) |
| 67 | soxr | [soxr.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soxr.yaml) |
| 68 | spacy | [spacy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/spacy.yaml) |
| 69 | srsly | [srsly.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/srsly.yaml) |
| 70 | swig | [swig.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/swig.yaml) |
| 71 | thinc | [thinc.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/thinc.yaml) |
| 72 | tiktoken | [tiktoken.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tiktoken.yaml) |
| 73 | tokenizers | [tokenizers.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tokenizers.yaml) |
| 74 | torch | [torch.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torch.yaml) |
| 75 | torchaudio | [torchaudio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchaudio.yaml) |
| 76 | torchvision | [torchvision.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchvision.yaml) |
| 77 | ujson | [ujson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ujson.yaml) |
| 78 | uv | [uv.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/uv.yaml) |
| 79 | xxhash | [xxhash.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/xxhash.yaml) |
| 80 | zope.interface | [zope.interface.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/zope.interface.yaml) |

（本表格由 GitHub Actions 自动生成）

---

## ⚙️ 自动化说明

- 每个包的构建规则定义在 `.github/workflows/` 目录下；
- 本工作流每天自动运行一次；
- 若检测到新增或删除的 YAML 文件，将自动更新 README；
- 当前的 `README.yaml` 文件不会被计入列表。

---

## 🕒 更新时间

- 世界标准时间 (UTC)：`2025-10-13 02:53:36`
- 北京时间 (Asia/Shanghai)：`2025-10-13 10:53:36`
