# BITCH-Lena-BENOIT-Gautier-HAMOUM-Bilal-BORIES-Luc

# TP2 M331

2. Créer le projet

B. Exécuter les tests unitaires

3. Les tests unitaires mettent autant de temps étant donné que la taille du tableau est conséquante (50 000 entiers : maxSize = 50000), il a donc 50 000 itérations à effectuer.

3. Intégrationn continue

A. S'assurer que le code de l'application ne comporte pas d'erreurs

2. Les tests ne passent plus étant donné que la méthode "reverseSort" n'est pas intégrée dans les accolades de la classe "SortAlgorithms".
4. Les autres membres du groupe se retrouve avec la même erreur une fois la récupération des derniers changements.
6. Nous obtenons une erreur lors de la compilation (build) du projet, nous avons reçu aussi un mail d'alerte disant qu'il y a une erreur dans le projet : 
Warning:  File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 2 source files to /home/runner/work/BITCH-Lena-BENOIT-Gautier-HAMOUM-Bilal-BORIES-Luc-/BITCH-Lena-BENOIT-Gautier-HAMOUM-Bilal-BORIES-Luc-/target/classes
[INFO] -------------------------------------------------------------
Error:  COMPILATION ERROR : 
[INFO] -------------------------------------------------------------
Error:  /home/runner/work/BITCH-Lena-BENOIT-Gautier-HAMOUM-Bilal-BORIES-Luc-/BITCH-Lena-BENOIT-Gautier-HAMOUM-Bilal-BORIES-Luc-/src/main/java/fr/unice/cdci/SortAlgorithms.java:[20,12] class, interface, or enum expected
[INFO] 1 error
[INFO] -------------------------------------------------------------
[INFO] ------------------------------------------------------------------------
[INFO] BUILD FAILURE
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  6.365 s
[INFO] Finished at: 2022-01-22T17:46:06Z
[INFO] ------------------------------------------------------------------------
Error:  Failed to execute goal org.apache.maven.plugins:maven-compiler-plugin:3.1:compile (default-compile) on project CDCI: Compilation failure
Error:  /home/runner/work/BITCH-Lena-BENOIT-Gautier-HAMOUM-Bilal-BORIES-Luc-/BITCH-Lena-BENOIT-Gautier-HAMOUM-Bilal-BORIES-Luc-/src/main/java/fr/unice/cdci/SortAlgorithms.java:[20,12] class, interface, or enum expected
Error:  -> [Help 1]
Error:  
Error:  To see the full stack trace of the errors, re-run Maven with the -e switch.
Error:  Re-run Maven using the -X switch to enable full debug logging.
Error:  
Error:  For more information about the errors and possible solutions, please read the following articles:
Error:  [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MojoFailureException
Error: Process completed with exit code 1.

9. Nous remarquons à la ligne 68 dans le test "badTest" que le assertTrue devant retourner true retourne false.
13. Nous récupérons une erreur du test lors du build.
