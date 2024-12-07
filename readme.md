#### Sample readme file for Emma ML application
* Will include a brief description and a place for notes about the project



####Steps to setting up and using Colab Notebooks.
* Step 1 create huggingface account and API key.  Login onto https://huggingface.co/ and creatte account.  
* Step 2 click top right button to get your profile information and click access tokens.  Click Create new token.  
	* Select correct permissions.  Try to add as much read/write permissions as you can.  I believe tokens should have access to most public models. 
	* Under search for Repositories permissions you can search for Neerajk4/my_awesome_model, and datasets/Neerajk4/my_awesome_dataset to gain access to this particular repository.
	* Click save and copy the token so that it is available to paste later on.
* Step 3 Add secrets to Google Colab. 
	* https://colab.research.google.com/.  In the open notebook options select Github.  In the search bar for repository enter Neerajk4/emma-ml and open notebook.
	* In the left hand side of the notebook, click secrets.  click add new secret.  name the token hf_token.  Then paste the value from the token created from huggingface account.
	* check Notebook access and save the token.

