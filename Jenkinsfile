import org.apache.tools.ant.types.Environment

pipeline {
    agent any
    environnement{
       NEW-VERSION = '1.3.0'
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                echo "cool ca marche ${NEW-VERSION}"
            }
        }
        
        stage('Nana') {
            steps {
                echo 'Hello Nana'
            }
        }
        stage('Moro') {
            steps {
                echo 'Hello Moro'
            }
        }
    }
}
