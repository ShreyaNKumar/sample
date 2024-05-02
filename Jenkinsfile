node {
    stage('Checkout') {
        git branch: 'main', url: "https://github.com/ShreyaNKumar/Demo2.git"
    }

    stage('Build') {
        // Any build steps you want to include
        echo 'Building ...'
    }

    stage('Deploy') {
        bat "copy *.html C:\\xampp\\htdocs\\"
    }
}
