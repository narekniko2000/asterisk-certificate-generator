# ASTERISK 1/10 YEAR CERTIFICATE GENERATOR README

1. Copy script to /etc/asterisk/keys
2. console: cd /etc/asterisk/keys
3. FOR TLS console: ./ast_tls_cert_10yrs.sh -C pbx-server-custom-name.local -O "company-custom-name" -d /etc/asterisk/keys
4. FOR CLIENTS console: 
	./ast_tls_cert_10yrs.sh -m client -c /etc/asterisk/keys/ca.crt -k /etc/asterisk/keys/ca.key -C pbx-server-custom-name.local -O "company-custom-name" -d /etc/asterisk/keys -o client
