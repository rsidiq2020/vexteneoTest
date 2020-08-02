# vexteneoTest
vexteneoTest

MySql:
	file: database/tester2.sql
	database: tester2
	user: root
	pass:
	
Drupal: (7.6.7)
	user: admin
	pass: 123

Step Install Drupal on Localhost:
1. Drupal version 7.72
2. create GIT repository and copy link for clone
3. using composer for install Drupal (run from command line)
	composer create-project drupal/recommended-project my_site_name_dir
4. create Mysql database (sample: tester)
5. run install Drupal, from localhost and set for database name (tester)
6. wait and see
