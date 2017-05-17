# tokenizationScript
-->Login to Unix terminal
-->Create a directory to work
	mkdir kishanSolution
-->copy the provided tar file here
	tar zxvf tokenizationScriptTest.tar.gz  -C .
-->Navigate to the scripts directory
	cd tokenizationScriptTest/scripts/
-->Run the script
	./replaceTokens.sh ../input/index.html ../conf/test.properties ../output/index.html
-->Verify the input and output files
	cat ../input/index.html ../output/index.html
