#Magnolia example clustering configuration

This is the example configuration for the Magnolia CMS clustering example explained in the blog post

http://lars-fischer-me/magnolia-workspace-clustering-tutorial

**Don't forget to include the database driver in the *lib* directory of the bundle instances!**

##Helpful database commands

mysql -u root -p

create database mgnl_cluster_public1;

create database mgnl_cluster_author;

create database mgnl_cluster_public2;

create database mgnl_cluster_forum;

###Remove the databases if needed

drop database mgnl_cluster_public1;

drop database mgnl_cluster_author;

drop database mgnl_cluster_public2;

drop database mgnl_cluster_forum;
