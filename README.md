## Aspect-based sentiment analysis
#### LPNU Course project

---

Before running code, please: 
- download [CoreNLP 4.5.7](https://stanfordnlp.github.io/CoreNLP/download.html) and place extracted *stanford-corenlp-4.5.7* directory to `/programming` directory.
- download [glove.6b.100d.txt](https://www.kaggle.com/datasets/danielwillgeorge/glove6b100dtxt) and place it to `/programming/preparing` folder
- install all dependencies
- run command from `/programming` directory:
```
export CORENLP_HOME=./stanford-corenlp-4.5.7
```
---

#### How to start the system:

---

Install all node modules by executing command from `/project-web-ui` directory:
```
npm install
```
Start web interface by executing command from `/project-web-ui` directory:
```
npm start
```
Start HTTP server by executing command from `/programming/api` directory:
```
python api_code.py
```

---
