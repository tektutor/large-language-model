# Large Language Model

## Installing Ollama on Linux
```
curl -fsSL https://ollama.com/install.sh | sh
```

Expected output
![image](https://github.com/user-attachments/assets/251a34b6-608a-4a3f-817d-de4153c2f9b1)
![image](https://github.com/user-attachments/assets/c0bdd829-1928-4926-af6d-291f06019376)

## Check the ollama version installed
```
ollama --version
ollama
```

Expected output
![image](https://github.com/user-attachments/assets/159e2d1d-3eaf-4020-a091-4d47a4d995ee)

## Download a model to run locally within Ollama
```
ollama pull llama3.2
```

Expected output
![image](https://github.com/user-attachments/assets/6f45efcc-406e-4d08-a453-ed69f8246a33)
![image](https://github.com/user-attachments/assets/37cd90ea-d574-427d-906e-fa5b00caa972)

## Run the model downloaded locally
```
ollama run llama3.2 "Can you explain what are your capabilities?"
```

Expected output
![image](https://github.com/user-attachments/assets/211772fb-981c-43e1-8070-f6b5f20b5843)


## Asking the model to write simple programs
```
ollama run llama3.2
Can you write a Hello World C++ Program?
```

Expected output
![image](https://github.com/user-attachments/assets/3abdefaf-ae0e-4df7-999f-7c10c976275e)

Follow up question
```
How to run this application
```
![image](https://github.com/user-attachments/assets/61cd3c33-6d67-483e-bed9-06794858e1a3)

Once you are done with your queries, you can quit
```
/bye
```
![image](https://github.com/user-attachments/assets/b9d95c78-3226-4f09-b288-79b82446e296)
