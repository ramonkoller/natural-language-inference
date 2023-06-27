# natural-language-inference
 
Auf diesem mehrsprachigen Datensatz https://www.kaggle.com/competitions/contradictory-my-dear-watson soll die Beziehung zweier Sätze herausgefunden werden.

In diesem Projekt wurde geprüft, ob die Performance besser wird, wenn zuerst alle Sätze ins Englische übersetzt werden und dann ein einsprachiges Transformer Model (RoBERTa) darauf finetuned. Zusätzlich wurde ein LSTM in PyTorch als Baseline trainiert.
