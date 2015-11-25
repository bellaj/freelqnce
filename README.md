# freelqnce
a WPF .Net application to manipulate a 3d Object (an ear) for medical use

Hot to use :


In the SQL server 
////////////////
1- creat a Database : ear
2- creat a table : Points_saved
3- the Points_saved table contains : 4 coulouns 

colx  
coly
colz
frame
color

the tpye for these coloumns is  varchar40
////////////////// 

In the V studio 
in the Mainwindwo.xaml.cs 

change the connexion string     myConnection = new SqlConnection("Server=KHALIDBELLAJ-PC;Database=ear;Trusted_Connection=True");

by your information(server...)

-------------

chen you start compilation you can add (marks) any point and when you restart again you'll get the previous points
