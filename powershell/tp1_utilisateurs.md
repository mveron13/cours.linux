$créer = Read-Host "Créer un nouvel utilisateur"

New-Localuser $créer


$modifier = Read-Host "Modifier l'utilisateur"

Set-LocalUser $modifier


$remove = Read-Host "Supprimer l'utilisateur"

Remove-LocalUser $remove


$obt = Read-Host "Obtenir une liste des utilisateurs"

Get-LocalUser $obt


$recup = Read-Host "Récupérer les informations d'un utilisateur spécifique"

Get-LocalUser -name $recup
