node('jenkins-slave') {
    
     stage('test pipeline') {
        sh(script: """
            echo "hello"
            
            git clone https://github.com/GalaxP/odporuc.git
            
            cd ./odporuc/odporuc.UI
            
            ls
            
            pwd
            
            kubectl get nodes
        """)
    }
}
