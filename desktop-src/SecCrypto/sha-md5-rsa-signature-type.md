---
Description: CSPs for PROV\_RSA\_SCHANNEL must support the CALG\_SSL3\_SHAMD5 hash that is compatible with the Microsoft Base Cryptographic Provider used in SSL 3.0 and TLS 1.0 client authentication.
ms.assetid: ca8be4fd-e7ca-4def-927d-b168628c566e
title: SHA/MD5 RSA Signature Type
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# SHA/MD5 RSA Signature Type

CSPs for PROV\_RSA\_SCHANNEL must support the CALG\_SSL3\_SHAMD5 [*hash*](https://msdn.microsoft.com/4165b820-30fc-477e-a690-81109f161323) that is compatible with the Microsoft Base Cryptographic Provider used in SSL 3.0 and TLS 1.0 client authentication. This hash consists of a concatenation of an [*MD5*](https://msdn.microsoft.com/4c4402e9-7455-4868-978f-3899a8fd86c1) hash and a SHA hash signed with an RSA or Diffie-Hellman private key. A handle to a hash value of this type is created by using the [**CryptCreateHash**](/windows/desktop/api/Wincrypt/nf-wincrypt-cryptcreatehash) or [**CPCreateHash**](https://www.bing.com/search?q=**CPCreateHash**) function with CALG\_SSL3\_SHAMD5 as the *Algid* parameter. Examples of using hash functions can be seen in [Example C Program: Creating and Hashing a Session Key](example-c-program-creating-and-hashing-a-session-key.md) and [Example C Program: Signing a Hash and Verifying the Hash Signature](example-c-program-signing-a-hash-and-verifying-the-hash-signature.md).

 

 


