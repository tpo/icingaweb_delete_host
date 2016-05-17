# icingaweb_delete_host
A script to delete a host from the icingaweb1/2 database

    usage: icingaweb_delete_host hostname
    
      This script will attempt to remove all entries of the given
      host from icingaweb(1+2).
    
      You need to run this script with sufficient permissions!
      (i.e. usually as the 'postgres' user)
    
      ATTENTION: PLEASE READ THE SOURCE CODE OF THE SCRIPT AND
                 ENSURE, THAT IT WILL NOT EAT YOUR SERVER.
                 This script has been tested under icinga2
                 V2.4.7-1~ppa1~trusty1.
