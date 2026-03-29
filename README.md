# 5-Methylcytosine-m5C-Modifications-Sites-in-RNA-Sequences

Place your FASTA file inside a folder (e.g., data/)
Example structure:
project/
├── main.py
├── data/
│   └── train.fasta
Update Dataset Path


Open main.py and modify the dataset path:


data_path = 'data/train.fasta'
Install Dependencies
pip install numpy pandas scikit-learn biopython xgboost catboost

If using GPU, set device ID:

os.environ["CUDA_VISIBLE_DEVICES"] = "0"
Change "0" to your GPU ID
Remove this line if running on CPU
Run the Script
python main.py



# 5-Methylcytosine (m5C) Modification Sites in RNA Sequences

## 

Place your FASTA file inside a folder (e.g., `data/`).

Example structure:

project/
├── main.py
├── data/
│ └── train.fasta



---

##  Update Dataset Path

Open `main.py` and modify the dataset path:

```python
data_path = 'data/train.fasta'


pip install numpy pandas scikit-learn biopython xgboost catboost

python main.py
