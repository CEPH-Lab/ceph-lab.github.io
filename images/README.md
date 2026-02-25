# CEPH Lab: Image Repository and Guidelines

This directory serves as the centralized repository for all visual assets associated with the Laboratory for Computational Epidemiology and Public Health (CEPH) website. To ensure the long-term stability, performance, and professional appearance of our digital presence, please adhere to the following standards when contributing or updating images.

## File Nomenclature and Architecture

The underlying architecture of our website utilizes specific routing protocols. To ensure the seamless integration of new visual assets, please observe the following conventions:

* **Standardized Naming:** Employ clear, concise, and lowercase filenames, utilizing hyphens to separate words (e.g., `marco-ajelli.jpg`). Avoid spaces or special characters to maintain strict cross-platform compatibility.

## Team Directory Profiles

When onboarding new members or updating existing profiles within the team directory, maintaining visual uniformity is essential for a cohesive presentation:

* **Aspect Ratio:** Before uploading, please crop all profile portraits to a precise 1:1 (square) aspect ratio. The site's cascading style sheets will automatically render these as uniform circular avatars; starting with a square origin ensures optimal centering and framing of the subject.
* **Optimization:** To preserve page loading speeds without sacrificing visual fidelity, please compress portrait files to under 1MB.
* **Implementation:** Reference the newly uploaded asset within the team page source code as follows, ensuring exact filename alignment:
    ```html
    <img src="images/firstname-lastname.jpg" alt="Firstname Lastname">
    ```

## Institutional Branding

The primary CEPH Lab logo (`ceph-logo.png`) must be maintained in a standard PNG format. This ensures the alpha channel (transparency) is preserved, allowing the insignia to integrate fluidly with the designated header styling and background palettes.
