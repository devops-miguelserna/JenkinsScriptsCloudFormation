node {
	stage 'Checkout'
		git url: 'https://github.com/miguel8810/CloudFormationLab.git', branch: 'fix_scripts'
	
	
	stage 'Ejecutor'
		sh "chmod +x ${WORKSPACE}/Build-Scripts/deploy.sh"
		sh "cd ${WORKSPACE}"
		sh "${WORKSPACE}/Build-Scripts/deploy.sh"

}