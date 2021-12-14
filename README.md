# First, open your IDE and click new project from version control
# Clone the repository from Github for example by HTTPS https://github.com/ElectronicPrescriptionProject/Project.git . A message will appear to load the Maven dependencies. Always load them.
# Build the project
# maven clean and install
# For the project to run, on JPA structure tab, right click the "DB connections" and add a new one. The type should be MySQL and the name of the database must be named patientsdb
# Same for the Database URL , it must end with the name patientsdb. Database username and password should be root and root by default. Clcik test connection to validate that the database is linked to the project correctly.
# If yes, press ok. The fields of the database will be added automatically
# Everything gets created automatically by the project on the database, except the drugs. On your database, you should add some drugs manually (for now, there are 2 drugs for testing, depon and ponstan).
# to run the project, go to src/main/java/com.eprescription.eprescription and run the EprescriptionApplication main class
# When run is over, go to your localhost on the port :8080. For example http://localhost:8080/
# You can use the application now. The database stores english and greek letters correctly, but due to the openPDF module used for export, it does not support greek fonts at all, so on the pdf only English characters can be # shown
# in case youre being redirected to an error page, make sure on the forms to fill the fields correctly. for example AMKA should contain 11 numbers, email should be someone@gmail.com form, etc.