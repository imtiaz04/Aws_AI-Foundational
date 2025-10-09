
Train a binary classification model using- Sagemaker to predict wether an email is spam or not.
Learn how to setup a sagemaker environment, import data, preprocess the data, train a model, evaluate the model & deploy it.
Requirements:
~>AWS- Account
~>AWS-Sagemaker studio setup

* SetUp SageMaker studio 
  ~>Launch sageMaker studio
  ~>Create a SageMaker Notebook
  ~>Prep the data
  ~>Train the Model
  ~>Evaluate the Model


Launch sageMaker studio:

<img width="625" height="392" alt="image" src="https://github.com/user-attachments/assets/d64bc026-8720-49e1-b256-41ad01a8135a" />

# Create sagemaker domain:

<img width="944" height="331" alt="image" src="https://github.com/user-attachments/assets/20d095a1-5119-42aa-9f34-b22624343f24" />

settingup single user:
<img width="932" height="374" alt="image" src="https://github.com/user-attachments/assets/5004eefc-c288-4f53-9b0f-0c4a695fd37f" />

confirm it started:

<img width="672" height="277" alt="image" src="https://github.com/user-attachments/assets/289321fc-255e-4ca7-bb3c-72f05c01ab89" />

Add user in user profile:

<img width="935" height="288" alt="image" src="https://github.com/user-attachments/assets/85d5da49-f354-473c-88e0-791aaa52afc5" />

<img width="787" height="367" alt="image" src="https://github.com/user-attachments/assets/2a38e873-5203-49aa-82d3-5db294388776" />

<img width="813" height="395" alt="image" src="https://github.com/user-attachments/assets/68439c27-33bb-400c-a77b-67b98f4f94e8" />

<img width="608" height="440" alt="image" src="https://github.com/user-attachments/assets/e21a2570-8254-45cf-a6ba-737521669bbc" />

<img width="596" height="169" alt="image" src="https://github.com/user-attachments/assets/25873d50-8664-4239-82da-a98480cfe1f6" />

Launching Notebook:

<img width="944" height="299" alt="image" src="https://github.com/user-attachments/assets/23285ee3-819d-4f7e-a583-891c9508f20c" />

Running the lab:

<img width="947" height="371" alt="image" src="https://github.com/user-attachments/assets/2bb1d57d-8717-4f45-927a-cdeaeae604ac" />

importing pandas:

<img width="427" height="235" alt="image" src="https://github.com/user-attachments/assets/1bc8a5f1-5c60-43b5-a502-503278d70343" />

Split the data and train the model:

<img width="681" height="296" alt="image" src="https://github.com/user-attachments/assets/b55d5f09-1b8d-46f1-b336-82380836c782" />

convert data into record set format and train model using linear.fit(train_records)

<img width="671" height="329" alt="image" src="https://github.com/user-attachments/assets/28b64e53-8eb9-4ab6-a34d-9742fed8a537" />

trainig job completed:

<img width="367" height="59" alt="image" src="https://github.com/user-attachments/assets/309859b1-00e4-455e-82db-523815e3e90f" />

Evaluating model:

<img width="578" height="359" alt="image" src="https://github.com/user-attachments/assets/318ad352-fa9c-41cb-9272-a792d8003a73" />

results:

<img width="199" height="57" alt="image" src="https://github.com/user-attachments/assets/471a4618-1967-42e2-bdeb-dde96cb19995" />

Creating confusion metrix:

<img width="727" height="316" alt="image" src="https://github.com/user-attachments/assets/ca9c3c26-5809-4e5b-a167-76c89af91ca1" />

metrix generated:

<img width="501" height="294" alt="image" src="https://github.com/user-attachments/assets/1293e361-9ba7-4a3b-99f1-16204d604066" />

Wrap-up:

Set-up Aws sagemaker studio and prepared data for machine learning.
Trained a simple binary classification model using sageMaker's Linear learner algorithm.
Evaluated the performance of the model using accuracy, presision, recall, and f1-score metrix.


















