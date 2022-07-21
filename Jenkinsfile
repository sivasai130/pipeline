pipeline{
agent any
stages{
stage('checkout'){
steps{
git' https://github.com/sivasai130/pipeline.git'
}
}
stage('builld'){
steps{
sh 'mvn clean install'
}
}
}
}

