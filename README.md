## An *encryption* *decryption* plugin using vanilla js
#### *Note: Do not trim the encrypted string.*
##### Steps to use mencdec
1. *Add this js file to your webpage*
    ```html
    <script src="https://cdn.jsdelivr.net/gh/mohan-askan/mencdec@master/mEncDec.js"></script>
    ```
2. *To encrypt a string*
    ```html
    <script type="text/javascript">
        var mencdec = new mEncDec("test123");
        var encrypt = mencdec.mencrypt();
        console.log(encrypt); // Output: æ÷áæ£ ¡
    </script>
    ```
3. *To decrypt a string*
    ```html
    <script type="text/javascript">
        var mencdec = new mEncDec("æ÷áæ£ ¡");
        var decrypt = mencdec.mdecrypt();
        console.log(decrypt); // Output: test123
    </script>
    ```
