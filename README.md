# Powershell

A collection of standalone PowerShell scripts for Windows 10/11, mostly security hardening, detection and system cleanup. Run them from an elevated PowerShell unless a script says otherwise.

## Scripts

**Endpoint protection and detection**

`AntivirusLite.ps1`, `GorstaksEDR.ps1`, `Sentinel.ps1`, `GShield.ps1`, `WindowsSecuritySuite.ps1`, `Guard.ps1`, `Guardian.ps1`, `GodsProtection.ps1`, `Unhooker.ps1`, `DragonBreathHunter.ps1`, `NeuroBehaviorMonitor.ps1`, `CursorTakeoverDetection.ps1`, `FakeUacDetection.ps1`, `RansomwareScarewareDetection.ps1`, `LNKProtection.ps1`, `CookieMonitor.ps1`, `Retaliate.ps1`, `KeyScrambler.ps1`, `ES.ps1`

**Hardening and policy**

`Hardening.ps1`, `Harden_AD.ps1`, `windows-security-hardening.ps1`, `GEDR_ASR_Rules.ps1`, `IPSecPolicy.ps1`, `IPBlock.ps1`, `GRules.ps1`, `CVE-MitigationPatcher.ps1`, `Creds.ps1`, `Browsers.ps1`, `NetworkDebloat.ps1`, `configure-dns-doh-dot.ps1`, `ExportCertsToReg.ps1`, `security-audit-6h.ps1`, `SecurityCheckup.ps1`

**Accounts**

`PasswordRotator.ps1`, `Install-PasswordRotator.ps1`, `DiagnoseAndFixLoginIssues.ps1`

**System cleanup and tuning**

`Stripper.ps1` (Windows ISO debloater), `BCDCleanup.ps1`, `Corrupt.ps1`, `Audio.ps1`, `GameCache.ps1`, `GPerf.ps1`, `ShowAllTrayIcons.ps1`

**Utilities**

`GFetch.ps1` (system info), `GKodi.ps1`, `Grok.ps1`, `Browser.ps1`, `OpenBookmarks.ps1`, `build.ps1`, `clone.ps1`, `push.ps1`

Each script has a header comment that describes what it does. Read it before running the script.

## Usage

```powershell
powershell -ExecutionPolicy Bypass -File .\<script>.ps1
```

Many of these scripts change system settings, services, firewall rules or accounts. Test on a non-critical machine first.

## Releases

`Releases/0.0.1/Powershell-0.0.1.zip` contains all scripts.
