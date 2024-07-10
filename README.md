## Generate terraform config for an existing resource in your subscription

1. Clone this repo and update the resources.tf file with the resourceId you need to import

2. Run terraform init

3. Run terraform plan -generate-config-out="<output-file-where-generated-config-will-be-stored>"

Ref: https://www.youtube.com/watch?v=SShHumn5Grc

Note: There are some third party tools available in market, you can also use those tools like aztfexport which is still in preview
