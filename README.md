# CYSE499_Neural_Language_Model

## Files
- `stage1_notebook.ipynb` — training pipeline, evaluation, and write-up
- `model_checkpoint/` — saved model + tokenizer (best validation
  checkpoint) (*Saved model too large for github and is stored on this google drive link:*)
- `public_test_predictions.csv` — predictions on `public_test.csv`
  (`id,predicted_label`)
- `requirements.txt` — pinned dependencies

## How to run
1. Install dependencies: `pip install -r requirements.txt`
2. Place `train.csv` and `public_test.csv` in the same directory as the
   notebook
3. Run `stage1_notebook.ipynb` top to bottom to reproduce training
4. The final 2 cells contain the testing, make sure model_checkpoint/ is downloaded and placed in the same directory as the notebook
