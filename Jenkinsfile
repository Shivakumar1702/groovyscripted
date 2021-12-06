node{
    if(env.TAG_NAME == "1.0"){
        stage('tag'){
            echo "taggg"
        }
    }
    if(env.BRANCH_NAME == 'master'){
        stage('build master'){
            echo "Building the Master"
        }
    }
    if(env.BRANCH_NAME == 'dev'){
        stage('build dev'){
            echo "building dev"
        }
    }
}
