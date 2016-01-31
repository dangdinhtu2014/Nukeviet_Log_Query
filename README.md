# Nukeviet_Log_Query
You can Log and count query in Nukeviet 4x to file and see all query to performance your website
#How to use
  Step 1:  change this file to folder Nukeviet 4.
  
  Step 2: Open file includes/footer.php
  
  search keyword "$db = null;" add this content before it 
  
  $db->logquery( NV_ROOTDIR . '/. NV_LOGS_DIR . '/query.sql' );// path file log quyery
  
  $step 3 : open path file log to see query
  

