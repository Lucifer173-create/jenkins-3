 pipeline {
agent any
stages {
stage('Clone Repository') {
steps {
git branch: 'main',
url: 'https://github.com/your-username/your-repo.git'
}
}
stage('Status') {
steps {
echo "Successfully fetched the repo"
}
}
}
}