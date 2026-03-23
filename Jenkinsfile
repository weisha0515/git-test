pipeline {
    agent any

    stages {
        stage('Git 操作') {
            steps {
                echo '执行 Git 操作'
                // 多个命令用 && 连接，或换行（\n），在同一个 Shell 进程中执行
                sh '''
                    cd /Users/weisha1/github/git-test
                    git pull origin master  # 此时已在 Git 仓库目录，可正常执行
                '''
            }
        }
        stage('Jenkins') {
            steps {
                echo 'Hello Jenkins1'
            }
        }
        stage('Job') {
            steps {
                echo 'Hello Job1'
            }
        }
    }
}