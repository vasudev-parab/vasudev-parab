pipeline{
agent any
stages
{
stage('Build')
{
steps{
echo "Building the code......"
bat "mvn clean"
}
}
stage('Test')
{
steps{
echo "testing the code...."
bat "mvn test"
}
}
stage('compile')
{
steps{
echo "compiling the project......"
bat "mvn compile"
}
}
stage('Deploy')
{
steps{
echo "Deploying the project"
}
}
}
}
