# Arcserve Unified Data Protection (UDP) unified install and setup
I led the small team that created the UX architecture of Arcserve Unified Data Protection (UDP), unifying CA/Arcserve's data protection portfolio into a single platform. Challenges included:
* Applications were built at different times, by different teams, using different UI technologies
* They protected data in different ways, e.g. separate applications for disk-based and image-based protection
* They supported different types of machines, e.g. physical and virtual machines
* Separate applications protected Linux, Windows, and Mac machines
* Different destinations (such as tape drives and backup disks) required separate applications

## Problem statement
After the successful spinoff of Arcserve on the strengths of Arcserve UDP, the applications still needed to be installed individually. A single installer was necessary.

Users reported difficulty finding the download from the home page, so the recommendation was made to launch the download from a prominent CTA.

## Deliverables
Wireframes that demonstrate the installer's goals:
* Download a small "shim" application that allows selection of components to download and install.
* New features like a EULA and Product Improvement Program enrollment.
* Parameters common across all components are set once, up front.
* "Express" installation uses smart (representative) default values; full install launches legacy installers.

These wireframes were user tested by Arcserve's UX researcher. 

<img height="300" alt="Screenshot 2026-08-07 173539" src="https://github.com/user-attachments/assets/75649460-a37d-4efa-a469-f52ce98aca50" />
<img height="300" alt="Screenshot 2026-08-07 124907" src="https://github.com/user-attachments/assets/4e9d781f-25e6-4588-8ad4-ef40c8c80dd9" />



<br><br>

Note: Axure RP prototypes don't do portability well, but you may download the .ZIP and extract to your local PC.
* Download the [Axure RP Extension for Chrome](https://chromewebstore.google.com/detail/axure-rp-extension-for-ch/dogkpdfcklifaemcdfbildhcofnopogp?hl=en-US) from the Google Chrome Web Store.
* Open the shortcut titled "Start Unified Install" to start.
