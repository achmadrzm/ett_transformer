# ETT-TRANSFORMER

---

## Dataset
ETT-small: https://github.com/zhouhaoyi/ETDataset/tree/main/ETT-small

---

## Device Specification
| Component | Specification |
| :--- | :--- |
| **Processor** | AMD Ryzen 5 5600XT |
| **GPU** | NVIDIA GeForce RTX 5060 8GB |
| **RAM** | 16 GB |
| **OS** | Windows 11 |
| **Python** | 3.13.13 |
| **CUDA Driver** | 13.2 (Runtime: 12.8) | 

----

## Installation

### 1. Clone repository
```bash
git clone https://github.com/achmadrzm/ett_transformer.git
```

```bash
cd ett_transformer
```

### 2. Create virtual environment
```bash
python -m venv transformer
```

### 3. Activate virtual environment
#### Windows:
```bash
transformer\Scripts\activate
```

#### Linux/MacOS:
```bash
source transformer/bin/activate
```

### 4. Install library
```bash
pip install --pre torch torchvision --index-url https://download.pytorch.org/whl/nightly/cu128
```

```bash
pip install -r requirements.txt
```