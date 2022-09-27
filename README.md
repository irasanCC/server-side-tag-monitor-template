# server-side-tag-monitor-template
The key deliverable of server side tag monitor is a BigQuery table that collects information about the Client that caused the tag(s) to fire, whether they fired successfully (or failed), how long the execution time of the tag was, and container details (id, version). 
The data will be sent by way of a Google Tag Manager custom template and a monitoring tag directly to the BigQuery table, and it will comprise statistics of all the tags (or a portion of it depending on the client's needs) that have fired on the website for any given dataLayer event.

