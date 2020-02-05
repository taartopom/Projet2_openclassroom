# Projet2_openclassroom
Après avoir exporté les tests initiaux qui indique les erreurs suivantes:<br><br>
- Pour le UserRepositoryTest:<br>
3 total, 2 error, 1 failed <br><br>

1.*error* **UserRepositoryTest.generateRandomUserWithSuccess**
java.lang.NullPointerException <br><br>
2.*failed* **UserRepositoryTest.getUsersWithSuccess**
java.lang.AssertionError<br><br>
3.*error* **UserRepositoryTest.deleteUserWithSuccess**
java.lang.NullPointerException<br><br>

- Pour le UserListInstrumentedTest:<br>
1 total, 1 error <br><br>

1.*error* **checkIfRemovingUserIsWorking**
java.lang.NullPointerException: Attempt to invoke interface method 'int java.util.List.size()' on a null object reference <br><br>

Le correctifs sont visibles dans les class:<br>

1. FakeApiService<br>
2. UserRepository<br>
*remplacer les TODO* <br><br>

Ensuite j'ai branché mon device (car la VM ne fonctionne pas sous W10 avec AMD mais pas d'inquiétude pour ce qui on un processeur Intel), là on peux supprimé un utilisateur et l'ajout fonctionne très bien en crée un nouvel utilisateur random.<br>


