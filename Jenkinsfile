def jobName = "${env.JOB_NAME}"
def PULL_REQUEST_NO = "${env.PULL_REQUEST_NO}"
def description = "<a href='https://github.snei.sony.com/sbolleddu/Multibranch-ci-test/pulls/$PULL_REQUEST_NO'> PR </a>"
currentBuild.setDescription(description)
Jenkins.instance.getItem(jobName.split('/')[0]).description = "<a href='https://github.snei.sony.com/sbolleddu/Multibranch-ci-test/pulls/$PULL_REQUEST_NO'> PR </a>"
