# Going inside the MongoDB pod:

'''  kubectl exec --stdin --tty {name of the pod} -n {namespace} -- /bin/bash '''

# Command to run mongo once inside the pod

''' mongo '''

# Command to show all databases

''' show dbs '''

# Command to use database

''' use {name_of_database}

# Command to list collections

'''  db.getCollection("resources").find({}) '''

# Command to clear database

'''  db.getCollection("resources").remove({}) '''

Note: In case of EMCO after clearing database you need to restart the orchestrator pod

