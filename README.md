# inventory-management- ddddddddddddddddd
import mysql.connector 
print(""" inventory management system""" )
mydb=mysql.connector.connect(host="localhost",user="root",password=("anshkb@0508"))
mycursor=mydb.cursor()
#mycursor.execute("create database sales")
mycursor.execute("use sales")
mycursor.execute("create table Login(username varchar(25) not null,password varchar(25) not null  )")
