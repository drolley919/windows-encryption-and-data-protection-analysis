# Analysis

Analysis focused on identifying and documenting BitLocker-protected storage volumes and evaluating methods available for forensic acquisition of encrypted media.

BitLocker status information was collected to determine encryption configuration, protection status, encryption algorithms, and volume accessibility. The examination confirmed the presence of a fully encrypted BitLocker volume protected through password and recovery-key mechanisms.

Recovery key information was successfully extracted using BitLocker management utilities. Access to recovery information enabled acquisition of the encrypted volume within a forensic environment while maintaining evidentiary integrity.

A logical acquisition of the encrypted volume was conducted using FTK Imager. Following acquisition, cryptographic hash values were generated and verified to confirm that evidence remained unchanged throughout the collection process.

Hash inventories and acquired artifacts were reviewed to validate acquisition completeness and ensure all collected files were successfully preserved for future forensic examination.
