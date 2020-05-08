pipeline{
agent any
stages {
stage('Deploy-dev'){
steps{
echo 'Hello'
}
}
stage('Deploy-QA'){
steps{
echo 'Hi'
  input "Does the staging env ok?"
}
}
stage('Deploy-Prod'){
steps{
echo 'How are u'
}
}
}
}

