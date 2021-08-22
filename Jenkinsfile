node('jenkins-slave') {
    
     stage('test pipeline') {
        sh(script: """
            echo "hello"
            
            git clone https://github.com/GalaxP/odporuc/tree/master/odporuc.UI
            
            cd ./odporuc/odporuc.UI
            
            ls
            
            pwd
            
            docker build . -t odporuc-ui
            
        
            
            docker images
        """)
    }
}
