# Nederlandse Sirene Pack gemaakt door Lars de Wolf <https://github.com/Lap76/NL-serversirens>

Momenteel zijn de enige serverside audio's die nederlands zijn:
 * oiss_ssa_vehaud_bcfd_new 
 * oiss_ssa_vehaud_bcso_new
 * oiss_ssa_vehaud_bcso_old
 * oiss_ssa_vehaud_sahp_bike
 * oiss_ssa_vehaud_lscofd_old
 * oiss_ssa_vehaud_lscofd_new	(Nieuwe Brandweer sirene update)
 * oiss_ssa_vehaud_sams_new 	(Nieuwe Ambulance sirene update)
 * oiss_ssa_vehaud_lspd_old	(Nieuwe Politie sirene update)
 * oiss_ssa_vehaud_sahp_new	(Nieuwe Politie motor+extra sirene update)
 * oiss_ssa_vehaud_fib_old	(Duits + Belgische sirene extra)

## MISS-ELS Config:

```
Config.AudioBanks = {
    --'DLC_WMSIRENS\\SIRENPACK_ONE',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_BCFD_NEW',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_BCSO_NEW',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_BCSO_OLD',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_SAHP_BIKE',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_LSCOFD_OLD',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_FIB_NEW', -- Optioneel voor admins/events amerikaanse sirenes
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_LSPD_NEW', -- Optioneel voor admins/events amerikaanse sirenes
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_LSCOFD_NEW',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_SAMS_NEW',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_LSPD_OLD',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_SAHP_NEW',
    'DLC_SERVERSIDEAUDIO\\OISS_SSA_VEHAUD_FIB_OLD', -- Optioneel Duits/Belgische sirenes
}
```

## Benodigde Scripts/Resources

* Warmenu - https://github.com/warxander/warmenu by warxander
* MISS-ELS - https://github.com/matsn0w/MISS-ELS by matsn0w

## MISS-ELS Config:

### Politie Noodhulp Updated:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_horn" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_adam" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_boy" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_charles" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_david" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" />
	</SOUNDS>
```
### Politie Noodhulp Extra:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_horn" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_new" AudioString="oiss_ssa_vehaud_sahp_new_siren_edward" SoundSet="OISS_SSA_VEHAUD_SAHP_NEW_SOUNDSET" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_edaward" SoundSet="OISS_SSA_VEHAUD_LSPD_OLD_SOUNDSET" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_adam" SoundSet="OISS_SSA_VEHAUD_LSPD_OLD_SOUNDSET" /> 
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_boy" SoundSet="OISS_SSA_VEHAUD_LSPD_OLD_SOUNDSET" />
	</SOUNDS>
```
### Politie Noodhulp:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_adam" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_boy" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_charles" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_david" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
	</SOUNDS>
```
### Politie Noodhulp Oud:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_charles" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_david" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_edward" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" /> 
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_edward" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
	</SOUNDS>
```
### Rijkspolitie Oud:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_edward" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_edward" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_charles" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_david" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
	</SOUNDS>
```
### KLPD:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_charles" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_david" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_edward" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" /> 
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_edward" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
	</SOUNDS>
```
### Politie VP Updated:
```
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_horn" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_charles" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" />
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_david" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_adam" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" /> 
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lspd_old" AudioString="oiss_ssa_vehaud_lspd_old_siren_boy" SoundSet="OISS_SSA_VEHAUD_lspd_old_SOUNDSET" />
	</SOUNDS>
```
### Politie VP:
```
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_charles" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_david" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_adam" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_boy" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
	</SOUNDS>
```
### Unmarked A: 
```
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_charles" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_david" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_charles" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_david" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
	</SOUNDS>
```
### Unmarked B: 
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_charles" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_david" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_charles" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_david" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
	</SOUNDS>
```
### Unmarked C: 
```
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_charles" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_david" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_charles" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" /> 
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_david" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
	</SOUNDS>
```
### Motor Updated:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_horn" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_new" AudioString="oiss_ssa_vehaud_sahp_new_siren_adam" SoundSet="oiss_ssa_vehaud_sahp_new_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_new" AudioString="oiss_ssa_vehaud_sahp_new_siren_boy" SoundSet="oiss_ssa_vehaud_sahp_new_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_new" AudioString="oiss_ssa_vehaud_sahp_new_siren_charles" SoundSet="oiss_ssa_vehaud_sahp_new_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_new" AudioString="oiss_ssa_vehaud_sahp_new_siren_david" SoundSet="oiss_ssa_vehaud_sahp_new_soundset" />
	</SOUNDS>
```
### Motor:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_horn" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_adam" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_boy" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_charles" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_david" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
	</SOUNDS>
```
### Motor v2:
```
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_horn" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_adam" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_boy" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_charles" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_david" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
	</SOUNDS>
```
### Ambulance Updated:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_horn" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_siren_adam" SoundSet="oiss_ssa_vehaud_sams_new_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_siren_boy" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_siren_charles" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_siren_david" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
	</SOUNDS>
```
### Ambulance MMT/Rapid Responder:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_horn" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_new" AudioString="oiss_ssa_vehaud_lscofd_new_siren_edward" SoundSet="oiss_ssa_vehaud_lscofd_new_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_siren_edward" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_siren_adam" SoundSet="oiss_ssa_vehaud_sams_new_soundset" /> 
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sams_new" AudioString="oiss_ssa_vehaud_sams_new_siren_boy" SoundSet="oiss_ssa_vehaud_sams_new_soundset" />
	</SOUNDS>
```
### Ambulance:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_horn" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_adam" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_boy" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_charles" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_david" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
	</SOUNDS>
```
### Ambulance oud:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_horn" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_old" AudioString="oiss_ssa_vehaud_lscofd_old_siren_edward" SoundSet="oiss_ssa_vehaud_lscofd_old_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_old" AudioString="oiss_ssa_vehaud_lscofd_old_siren_boy" SoundSet="oiss_ssa_vehaud_lscofd_old_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_old" AudioString="oiss_ssa_vehaud_lscofd_old_siren_charles" SoundSet="oiss_ssa_vehaud_lscofd_old_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_old" AudioString="oiss_ssa_vehaud_lscofd_old_siren_david" SoundSet="oiss_ssa_vehaud_lscofd_old_soundset" />
	</SOUNDS>
```
### Brandweer Updated:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_horn" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_new" AudioString="oiss_ssa_vehaud_lscofd_new_siren_adam" SoundSet="oiss_ssa_vehaud_lscofd_new_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_new" AudioString="oiss_ssa_vehaud_lscofd_new_siren_boy" SoundSet="oiss_ssa_vehaud_lscofd_new_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_new" AudioString="oiss_ssa_vehaud_lscofd_new_siren_charles" SoundSet="oiss_ssa_vehaud_lscofd_new_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_lscofd_new" AudioString="oiss_ssa_vehaud_lscofd_new_siren_david" SoundSet="oiss_ssa_vehaud_lscofd_new_soundset" />
	</SOUNDS>
```
### Brandweer Nieuw:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_horn" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_charles" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_david" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_adam" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" /> 
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_boy" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
	</SOUNDS>
```
### Brandweer Oud:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_horn" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_adam" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_boy" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_charles" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_david" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
	</SOUNDS>
```
### Brandweer SIV/Auto:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_adam" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="oiss_ssa_vehaud_bcso_new_siren_boy" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_charles" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_david" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
	</SOUNDS>
```
### Brandweer SIV/Auto Oud:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_new" AudioString="OISS_SSA_VEHAUD_BCSO_NEW_HORN" SoundSet="OISS_SSA_VEHAUD_BCSO_NEW_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_sahp_bike" AudioString="oiss_ssa_vehaud_sahp_bike_siren_edward" SoundSet="oiss_ssa_vehaud_sahp_bike_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcso_old" AudioString="oiss_ssa_vehaud_bcso_old_siren_edward" SoundSet="oiss_ssa_vehaud_bcso_old_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_charles" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_bcfd_new" AudioString="oiss_ssa_vehaud_bcfd_new_siren_david" SoundSet="oiss_ssa_vehaud_bcfd_new_soundset" />
	</SOUNDS>
```
### Duits + Belgishe Sirenes:
```	
	<SOUNDS>
		<MainHorn AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_fib_old" AudioString="OISS_SSA_VEHAUD_FIB_OLD_HORN" SoundSet="OISS_SSA_VEHAUD_FIB_OLD_SOUNDSET" />
		<NineMode AllowUse="false" />
		<SrnTone1 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_fib_old" AudioString="oiss_ssa_vehaud_fib_old_siren_adam" SoundSet="oiss_ssa_vehaud_fib_old_soundset" /> 
		<SrnTone2 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_fib_old" AudioString="oiss_ssa_vehaud_fib_old_siren_boy" SoundSet="oiss_ssa_vehaud_fib_old_soundset" />
		<SrnTone3 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_fib_old" AudioString="oiss_ssa_vehaud_fib_old_siren_charles" SoundSet="oiss_ssa_vehaud_fib_old_soundset" />
		<SrnTone4 AllowUse="true" SoundBank="dlc_serversideaudio/oiss_ssa_vehaud_fib_old" AudioString="oiss_ssa_vehaud_fib_old_siren_david" SoundSet="oiss_ssa_vehaud_fib_old_soundset" />
	</SOUNDS>
```

## Authors

Contributors names and contact info

Larsdewolf discord: @Larsdewolf  

## Version History

* 1.0
    * Initial Release

## Acknowledgments

Inspiration, code snippets, etc.
* [fk-1997] (https://github.com/fk-1997/Server-Sided-Sounds-and-Sirens/tree/main)https://github.com/fk-1997/Server-Sided-Sounds-and-Sirens/tree/main)
