#Doordat het in de loop zit kun je meerdere OU's aanmaken, en als de OU invalid zou zijn
while($true)
{

    #Vraagt user voor OU naam"
    $OU_Name = Read-Host "Geef de naam voor de nieuwe OU: "

    #Checkt als de lengte van de string "OU_Name" kleiner is dan 1 of groter is dan 64.Dit zijn de enige restrictions voor een OU
    #te benoemen volgens de Microsoft-documentatie: https://docs.microsoft.com/en-us/troubleshoot/windows-server/identity/naming-conventions-for-computer-domain-site-ou

    if($OU_Name.Length -lt 1 -or $OU_Name.Length -gt 64 )
    {
        Write-Host "Een OU mag niet langer zijn dan 64 karakters en moet minimaal 1 karakter bevatten."
    }

    else
    {
        Write-Host "Een OU met de naam" $OU_Name "zal gemaakt worden."
        New-ADOrganizationalUnit -Name $OU_Name -Path "DC=GLLOCAL,DC=TEST"
        $GUID = Get-ADOrganizationalUnit -Filter 'Name -like $OU_Name' | Select ObjectGUID
        Write-Host $GUID
        #Als de volgende lijn uncommented is, kun je het script gebruiken om enkel maar 1 OU te maken per keer dat je dit script runt.
        #exit
    }
    

    


}
