# ImageClassification
Docker :whale: + MongoDB :four_leaf_clover: + Flask :maple_leaf: + Tensorflow :jack_o_lantern:

## Run for Sentence Similarity
1) Up the containers
```
cd SentenceSimilarity
sudo docker-compose build
sudo docker-compose up
```
2) POST the request to **localhost:/register** in the **POSTMAN**
```
{"username": "mehmed", "password": "123"}
``` 
3) POST the request to **localhost:/detect** in the **POSTMAN**
```
{"username": "mehmed", "password": "123", "text1":"This is a dog", "text2":"This is a human"}
```

