 1. Créer un Web service qui permet de :

  • Convertir un montant de l’euro en DH 

  • Consulter un Compte 

  • Consulter une Liste de comptes


![1-Classe BanqueService](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/1a341421-d296-4d6b-8534-2bf9cc2f3ba6)
# classe Compte :
![1-Classe Compte](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/c8fdfbce-a89b-4bb4-9f30-422a9607311e)

2. Déployer le Web service avec un simple Serveur JaxWS

![2](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/bf3e8a4e-5571-4241-97ed-30d8caceda0b)

3. Consulter et analyser le WSDL avec un Browser HTTP
WSDL : 
![3-WSDL](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/3e96ffc4-a111-4f3c-bd7d-a0993c366164)

XSD : 
![3-XSD](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/85fd2b8b-a90d-4bc7-9bfb-3df04974c0ee)


4. Tester les opérations du web service avec un outil comme SoapUI
![4](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/b51740d0-676b-4985-abe2-3237e5b59ba3)

    Teste de conversion :
![4 Teste de conversion](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/378d3e97-2224-435e-b968-d7ae11ce01c9)

    Teste getCompte :
![4 teste getCompte](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/d6c90805-bb1e-4552-9ffd-e4e832f66f93)

    tester listCompte :
![4 tester listCompte](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/da2278c9-02e1-40c1-9ac6-34d8a3dccf49)


5. Créer un Client SOAP Java
      - Générer le Stub à partir du WSDL
      - Créer un client SOAP pour le web service
  
![5](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/3d2fb014-8040-4610-b275-51ae1e908b5f)

Main.java : 
![5 main java](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/aec8fc06-3458-4fff-925c-59246d22f767)

--
![5 result](https://github.com/MansourAnas1/TP5-Web-services-SOAP-WSDL-AnasMansour-MIAAD-/assets/167020036/7fb12ba8-e793-456a-91a1-618793d3f2db)

