@Library('jenkins-shared-library')_

def configMap= [
    projectname : "roboshop",
    directory : "user"
]

// echo "now we are executing the user"
echo "now we are executing the user in feature_branch"

if( env.BRANCH_NAME.equalsIgnoreCase("main") ){
    echo "please folow the RP"
}
else{
    NodeJenkins(configMap)
}