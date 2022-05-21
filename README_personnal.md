core/websock.js ligne 251 => ++this.sendString(document.location.hash.slice(1)+"\n");
utils/novnc_proxy ligne 183 => ~~if ! ps -o pid | grep ${proxy_pid} >/dev/null; then


./utils/novnc_proxy --key /home/hugo/final_version/private/rsa_sha256_key.pem --cert /home/hugo/final_version/private/rsa_sha256_cert.pem --vnc 172.21.143.164:8080