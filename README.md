# First-repo-from-Terraform
#My first resource created in GIT from terraform 

provider "github" {
    token="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"
  
}


resource "github_repository" "example" {
  name        = "First-repo-from-Terraform"
  description = "My first resource created in GIT from terraform "

  visibility = "public"
  auto_init = true

  
}
