pipeline {
    agent any
     parameters('run monitor') {
         string(name: 'WEBSITE_URL', defaultvalue: 'www.google.com', desceription: 'the website to monitor')
     }
     stages {
            stage('monitor') {
                steps {
                    bat '"C:\\Program Files\\Git\\bin\\bash.exe "chmod +x monitor.sh && ./monitor.sh"'
                }
            }
     }
     }
}