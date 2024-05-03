node {
    stage('Checkout') {
        git branch: 'main', url: "https://github.com/ShreyaNKumar/Demo2.git"
    }

    stage('Deploy') {
        bat "copy *.html C:\\xampp\\htdocs\\"
    }
}
