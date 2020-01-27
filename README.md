ata = open('cert2.txt').read()
	cert = TLSCertificate()

	print cert.loadCertificate(data)

	# print "hello world"
