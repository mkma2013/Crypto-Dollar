Invoke-Command -ComputerName SEA-SVR1 {
    Install-WindowsFeature -Name AD-Domain-Services
}
