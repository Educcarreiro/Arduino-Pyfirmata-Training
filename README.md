# Arduino-Pyfirmata-Training
Python &amp; Arduino

Instalações necessárias 

* Pyfirmata ( Prompt Conda - pip install pyfirmata)

* Mediapipe (Prompt Conda -  pip install mediapipe) 

Devido a atualização do python 3.11.5 ocorre um erro  porque o método inspect.getargspec() foi removido no Python 3.5 e substituído por inspect.getfullargspec(). Corrigi isso editando a biblioteca PyFirmata, alterando inspect.getfullargspec() em vez de inspect.getargspec().
