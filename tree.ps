$path = Get-Location
$output = "README.md"

function Get-Tree {
    param (
        [string]$Path,
        [string]$Prefix = ""
    )
    $items = Get-ChildItem -Path $Path -Exclude 'node_modules'
    foreach ($item in $items) {
        if ($item.PSIsContainer) {
            "$Prefix├── $($item.Name)" | Out-File -FilePath $output -Append
            Get-Tree -Path $item.FullName -Prefix "$Prefix│   "
        } else {
            "$Prefix├── $($item.Name)" | Out-File -FilePath $output -Append
        }
    }
}

"# Project Structure" | Out-File -FilePath $output
"" | Out-File -FilePath $output -Append
Get-Tree -Path $path
