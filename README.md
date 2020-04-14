# ATM-for-the-Visually-Impaired-

PYTHON  MINI Project : 

LIBRARIES USED: pyttsx3 , random, gtts, speech_recognition , os, csv, getpass_ak , datetime .

* The model ATM system is mainly developed to make it accessible for the visually impaired people , 
  the code written in python3 mainly uses the libraries : pyttsx3 for speech to voice converison and 
  speech_recognition to use the mic for speech to text , it utilizes the GOOGLE's API service for voice recognition.
  
* The transactions performed are locally stored in a CSV file , there are 5-6 preloaded accounts with pin and account
  numbers and names.
  
* The model involves cash withdarwal , cash deposit and balance inquiry and pin change functions whcih are all voice 
  controlled and keypad controlled.
  
* All errors have been handled diligently and special security features have been added such as:
  i) Account number has to be 16 digits and the password has to be 4 digits .
  ii)A max for 3 illegal entries is allowed and after that the programme will terminate itself.
  iii)Any wrong or illegal input wil result in programme termination (similar to a real ATM).
  iv)integrity of each input has been checked and only then accepted.
  
* A personalized library has been imported for displaying '*' for password input to make it more secure .

  
  
  
** NOTE : THE PROGRAMME REQUIRES A GOOD NETWORK CONNECTION AND A QUIET BACKGROUUND FOR SPEECH RECOGNITION.

  




