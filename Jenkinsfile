pipeline { 
    agent any 
 
    stages { 
 
        stage('Clone Code') { 
            steps { 
                git branch:'main', 
                url:'https://github.com/sanjaysanju150809-blip/jenkins-demo-'
            } 
        } 
 
        stage('Compile Code') { 
            steps { 
                bat 'javac demo.java' 
            } 
        }
          stage('Run Code') { 
            steps { 
                bat 'java demo' 
            } 
        } 
 
    } 
} 
