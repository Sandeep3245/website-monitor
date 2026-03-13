pipeline {
    agent any
    
    // This creates the text box to ask for the website URL
    parameters {
        string(name: 'WEBSITE_URL', defaultValue: 'google.com', description: 'Which website should I ping?')
    }
    
    stages {
        stage('Monitor Website') {
            steps {
                bat '"C:\\Program Files\\Git\\bin\\bash.exe" -c "chmod +x monitor.sh && ./monitor.sh"'
            }
        }
    }
}