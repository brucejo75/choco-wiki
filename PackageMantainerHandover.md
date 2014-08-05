# Package Maintainer Handover

When a package maintainer is deemed no longer maintaining a package, a new maintainer or maintainers can assist and/or takeover. 

This is done through the Package Triage Process.

An admin will make you a maintainer, you will need to click on the link in your email to confirm.

Once that is done you have several steps:

 * Obtain the source for the package. Look for the maintainer's profile to see if they have a GitHub repository for their packages. If you don't find it there, attempt to find it on GitHub with some google-fu.
 * If all else fails, download the package from the website (use the Download link on the left side).
 * Use unzip to unpack the package and remove the files that are only used in packaging.
 * Put that in your GitHub repository for packages. 
 * Ensure you have a link to that repository in your chocolatey profile.
 * Check in the package as is prior to any changes. If you are moving it over from another repository, just copy the current files/folders related to that package into your repository. 
 * Now make your changes/fixes/updates.
 * One thing to update is any links to the old repository such as images and/or maintainers.
 * If brought in from another repository, be sure to send a Pull Request to that repository to have the package removed from there (or at the very least file an issue). Link the new location in that request for others who might be searching.