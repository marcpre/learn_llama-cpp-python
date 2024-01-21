# learn_llama-cpp-python

## Install `llama-cpp-python` on Windows

### 1. Install Visual Studio with:
C++ CMake tools for Windows.
C++ core features
Windows 10/11 SDK.

Visual Studio 2022 Enterprise with required components installed.

### 2. CUDA Toolkit:

Download and install CUDA Toolkit 12.2 from NVIDIA’s official website.
Verify the installation with `nvcc --version` and nvidia-smi.

### 3. Install

```
D:\Code\llama_cpp>pip install llama-cpp-python --force-reinstall --upgrade --no-cache-dir
Collecting llama-cpp-python
  Downloading llama_cpp_python-0.2.31.tar.gz (9.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 9.7/9.7 MB 6.2 MB/s eta 0:00:00
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Installing backend dependencies ... done
  Preparing metadata (pyproject.toml) ... done
Collecting diskcache>=5.6.1
  Downloading diskcache-5.6.3-py3-none-any.whl (45 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 45.5/45.5 kB ? eta 0:00:00
Collecting typing-extensions>=4.5.0
  Downloading typing_extensions-4.9.0-py3-none-any.whl (32 kB)
Collecting numpy>=1.20.0
  Downloading numpy-1.26.3-cp310-cp310-win_amd64.whl (15.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 15.8/15.8 MB 5.0 MB/s eta 0:00:00
Collecting jinja2>=2.11.3
  Downloading Jinja2-3.1.3-py3-none-any.whl (133 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.2/133.2 kB 7.7 MB/s eta 0:00:00
Collecting MarkupSafe>=2.0
  Downloading MarkupSafe-2.1.4-cp310-cp310-win_amd64.whl (17 kB)
Building wheels for collected packages: llama-cpp-python
  Building wheel for llama-cpp-python (pyproject.toml) ... done
  Created wheel for llama-cpp-python: filename=llama_cpp_python-0.2.31-cp310-cp310-win_amd64.whl size=9110107 sha256=b4368a0b71da7f3a8d33a622809130c54ac055e082c2ad380ed13e35c1e61f6a
  Stored in directory: C:\Users\user\AppData\Local\Temp\pip-ephem-wheel-cache-fuvb2gsb\wheels\26\8c\d2\2432edacf8fe69a190cc2a462fa5aea8eaf13f79c1efdbf6d7
Successfully built llama-cpp-python
Installing collected packages: typing-extensions, numpy, MarkupSafe, diskcache, jinja2, llama-cpp-python
Successfully installed MarkupSafe-2.1.4 diskcache-5.6.3 jinja2-3.1.3 llama-cpp-python-0.2.31 numpy-1.26.3 typing-extensions-4.9.0

[notice] A new release of pip available: 22.2.1 -> 23.3.2
[notice] To update, run: python.exe -m pip install --upgrade pip

```


