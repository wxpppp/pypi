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
| 11 | confluent-kafka | [confluent-kafka.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/confluent-kafka.yaml) |
| 12 | contourpy | [contourpy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/contourpy.yaml) |
| 13 | crc32c | [crc32c.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/crc32c.yaml) |
| 14 | cryptography | [cryptography.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cryptography.yaml) |
| 15 | ctranslate2 | [ctranslate2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ctranslate2.yaml) |
| 16 | cymem | [cymem.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/cymem.yaml) |
| 17 | faiss-cpu | [faiss-cpu.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/faiss-cpu.yaml) |
| 18 | gevent | [gevent.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/gevent.yaml) |
| 19 | greenlet | [greenlet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/greenlet.yaml) |
| 20 | grpcio-tools | [grpcio-tools.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio-tools.yaml) |
| 21 | grpcio | [grpcio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/grpcio.yaml) |
| 22 | h5py | [h5py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/h5py.yaml) |
| 23 | hf-xet | [hf-xet.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/hf-xet.yaml) |
| 24 | jiter | [jiter.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/jiter.yaml) |
| 25 | kiwisolver | [kiwisolver.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kiwisolver.yaml) |
| 26 | kornia-rs | [kornia-rs.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/kornia-rs.yaml) |
| 27 | lintrunner | [lintrunner.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lintrunner.yaml) |
| 28 | llama-cpp-python | [llama-cpp-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llama-cpp-python.yaml) |
| 29 | llguidance | [llguidance.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llguidance.yaml) |
| 30 | llvmlite | [llvmlite.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/llvmlite.yaml) |
| 31 | lxml | [lxml.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/lxml.yaml) |
| 32 | matplotlib | [matplotlib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/matplotlib.yaml) |
| 33 | maturin | [maturin.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/maturin.yaml) |
| 34 | ml_dtypes | [ml_dtypes.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ml_dtypes.yaml) |
| 35 | msgpack | [msgpack.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/msgpack.yaml) |
| 36 | nh3 | [nh3.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nh3.yaml) |
| 37 | ninja | [ninja.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ninja.yaml) |
| 38 | nlopt | [nlopt.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/nlopt.yaml) |
| 39 | numba | [numba.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numba.yaml) |
| 40 | numpy | [numpy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/numpy.yaml) |
| 41 | onnx | [onnx.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnx.yaml) |
| 42 | onnxruntime | [onnxruntime.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/onnxruntime.yaml) |
| 43 | opencv-contrib-python-headless | [opencv-contrib-python-headless.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-contrib-python-headless.yaml) |
| 44 | opencv-contrib-python | [opencv-contrib-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-contrib-python.yaml) |
| 45 | opencv-python-headlees-rolling | [opencv-python-headlees-rolling.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-headlees-rolling.yaml) |
| 46 | opencv-python-headless | [opencv-python-headless.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-headless.yaml) |
| 47 | opencv-python-rolling | [opencv-python-rolling.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python-rolling.yaml) |
| 48 | opencv-python | [opencv-python.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/opencv-python.yaml) |
| 49 | optree | [optree.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/optree.yaml) |
| 50 | orjson | [orjson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/orjson.yaml) |
| 51 | pandas | [pandas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pandas.yaml) |
| 52 | patchelf | [patchelf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/patchelf.yaml) |
| 53 | pillow | [pillow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pillow.yaml) |
| 54 | preshed | [preshed.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/preshed.yaml) |
| 55 | psycopg-binary | [psycopg-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg-binary.yaml) |
| 56 | psycopg2-binary | [psycopg2-binary.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/psycopg2-binary.yaml) |
| 57 | pyarrow | [pyarrow.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pyarrow.yaml) |
| 58 | pydantic-core | [pydantic-core.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pydantic-core.yaml) |
| 59 | pygit2 | [pygit2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pygit2.yaml) |
| 60 | pymupdf | [pymupdf.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pymupdf.yaml) |
| 61 | pypdfium2 | [pypdfium2.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/pypdfium2.yaml) |
| 62 | regex | [regex.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/regex.yaml) |
| 63 | rpds-py | [rpds-py.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/rpds-py.yaml) |
| 64 | ruamel-yaml-clib | [ruamel-yaml-clib.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruamel-yaml-clib.yaml) |
| 65 | ruff | [ruff.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ruff.yaml) |
| 66 | safetensors | [safetensors.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/safetensors.yaml) |
| 67 | scikit-learn | [scikit-learn.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scikit-learn.yaml) |
| 68 | scipy-openblas | [scipy-openblas.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy-openblas.yaml) |
| 69 | scipy | [scipy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/scipy.yaml) |
| 70 | sentencepiece | [sentencepiece.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/sentencepiece.yaml) |
| 71 | shapely | [shapely.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/shapely.yaml) |
| 72 | soundfile | [soundfile.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soundfile.yaml) |
| 73 | soxr | [soxr.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/soxr.yaml) |
| 74 | spacy | [spacy.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/spacy.yaml) |
| 75 | srsly | [srsly.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/srsly.yaml) |
| 76 | swig | [swig.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/swig.yaml) |
| 77 | thinc | [thinc.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/thinc.yaml) |
| 78 | tiktoken | [tiktoken.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tiktoken.yaml) |
| 79 | tokenizers | [tokenizers.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/tokenizers.yaml) |
| 80 | torch | [torch.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torch.yaml) |
| 81 | torchaudio | [torchaudio.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchaudio.yaml) |
| 82 | torchvision | [torchvision.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/torchvision.yaml) |
| 83 | ujson | [ujson.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/ujson.yaml) |
| 84 | uv | [uv.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/uv.yaml) |
| 85 | uvloop | [uvloop.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/uvloop.yaml) |
| 86 | xxhash | [xxhash.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/xxhash.yaml) |
| 87 | zope.interface | [zope.interface.yaml](https://github.com/Loongson-Cloud-Community/pypi/blob/main/.github/workflows/zope.interface.yaml) |

（本表格由 GitHub Actions 自动生成）

---

## ⚙️ 自动化说明

- 每个包的构建规则定义在 `.github/workflows/` 目录下；
- 工作流每天自动运行一次；
- 若检测到新增或删除的 YAML 文件，将自动更新 README；
