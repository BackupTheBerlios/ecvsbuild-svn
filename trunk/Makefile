main:
	chmod +x installer
	./installer

clean: uninstall
	touch lib
	rm -rfv lib
	
uninstall:
	touch ~/bin/ecvsbuild
	rm ~/bin/ecvsbuild
	touch ~/.ecvsbuildrc
	rm ~/.ecvsbuildrc
	touch ~/.ecvsbuildrc_config
	rm ~/.ecvsbuildrc_config
