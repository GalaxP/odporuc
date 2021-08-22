node('jenkins-slave') {
    
     stage('test pipeline') {
        sh(script: """
            echo "hello"
            
            git clone https://github.com/GalaxP/odporuc.git
            
            cd ./odporuc/odporuc.UI
            
            ls
            
            pwd
            
            sudo docker build . -t odporuc-ui
            
       
            sudo docker images
        """)
    }
}
