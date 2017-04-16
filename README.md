# Pixels
A simple Discord theme

//META{"name":"Pixels","description":"Simple theme by 0zes","version":"1.000"}*//{}
/* "Pixels by @ffOzes */
/* By 0zes and thanks to Zerthox for the code */

/* IMPORT CSS FROM GITHUB */
@import url(https://gitcdn.xyz/repo/Zerthox/ClearVision/master/css/ClearVision_v5.min.css);
/*

/*
---------------------------------------------------------------------------------------------------------------------------------------------
============== CHANGER LES COULEURS ===============
*/
:root {
	--main-color: #607058;
	--hover-color: #183000;
    --background-blur: 0px;
    --background-brightness: 100%;
}
/*
--------------------------------------------------------------------------------------------------------------------------------------------
*/
/*
---------------------------------------------------------------------------------------------------------------------------------------------
========= CHANGER LE FOND ==========
*/
body::after,
.callout-backdrop,
.user-popout::before,
#user-profile-modal .header::before,
#pubs-container::before,
.auth-background,
.auth-tiling-bg,
.invite-modal .invite-splash,
.radio-theme.light label,
.radio-theme.dark label{
    background-image: url(https://danglingmouse.com/wp-content/uploads/2014/11/11-GqfEdJC.png) !important; /* IMPORTANT: Le lien doit commencer par HTTPS! */
}
/*
--------------------------------------------------------------------------------------------------------------------------------------------
*/
