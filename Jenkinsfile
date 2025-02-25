pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/kishore-2025/demo2_rep.git'
}
}
stage('build')
{
steps(
sh 'javac hello.java'
}
}
}
}

