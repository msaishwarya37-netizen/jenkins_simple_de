pipeline{
   agent any
Stages{
stages('clone'){
 steps{
  git url:'https://github.com/msaishwarya37-netizen/jenkins_simple_de.git',
  branch:'main'
}
}
Stages('Run script'){
steps{
sh'chmod+xscript.sh'
sh'./script.sh'
}
}
}
}
