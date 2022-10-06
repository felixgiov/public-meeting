# SMT OCR Error Correction Tool

1. Download and unzip Moses and the model: `https://lotus.kuee.kyoto-u.ac.jp/~felix/ocr_smt/moses.zip`

2. Change the paths in the config file (`./moses/OCR/tune/mert-work/moses.ini`) to your machine's paths.

3. Convert the input text into the following format: `I n <space> m e m o r y <space> o f <space> t h e <space> l a t e`.

4. Run the SMT OCR Error Correction model: `./moses/bin/moses -config ./moses/OCR/tune/mert-work/moses.ini -input-file input_sample.txt > output_sample.txt`
