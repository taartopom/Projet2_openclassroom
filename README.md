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
3.
