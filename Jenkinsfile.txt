Pipeline
{
agents any
{
stages
{
stage('Git Checkout')
{
Steps
{
git 'https://github.com/santsm/maven.git'
}
}
stage('Maven Build')
{
steps
{
sh 'mvn build'
}
}
}}