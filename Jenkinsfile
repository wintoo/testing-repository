def jobName = "${env.JOB_NAME}"

def PULL_REQUEST_NO = "${env.PULL_REQUEST_NO}"

def description = "<a href='https://github.com/wintoo/testing-repository/pulls'> PR </a>"

currentBuild.setDescription(description)

Jenkins.instance.getItem(jobName.split('/')[0]).description = "<a href='https://github.com/wintoo/testing-repository/pulls'> PR </a>"
