<!-- 
# Habilite o CertificateManager
```gcloud services enable certificatemanager.googleapis.com```

# Criando Mapa de Certificados
```gcloud certificate-manager maps create certificate-map-demo```

# Criando Certificado Gerenciado pelo Google Cloud
```gcloud certificate-manager certificates create play-certificate --domains="play.devopslabs.cloud"  ```

# Criando entrada no Mapa de certificados
```gcloud certificate-manager maps entries create play-certificate-map-entry --map=certificate-map-demo --hostname=play.devopslabs.cloud --certificates=play-certificate```



gcloud certificate-manager maps entries delete play-certificate-map-entry \
   --map=certificate-map-demo  -->