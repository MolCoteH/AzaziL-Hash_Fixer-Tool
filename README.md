# AzaziL-Hash_Fixer-Tool

The **AzaziL-Hash_Fixer-Tool** is a command-line program designed to repair damaged hashes by removing illegal characters and optionally converting uppercase characters to lowercase. It is a simple and efficient tool that can be used in various scenarios where the integrity of hash values needs to be restored.

## How to Use

1. Ensure that you have Python installed on your system.

2. Download or clone the **AzaziL-Hash_Fixer-Tool** repository from GitHub.

3. Open a terminal or command prompt and navigate to the directory where the program is located.

4. Run the program by executing the following command:

   ```
   python azazil_hash_fixer_tool.py
   ```

5. The program will prompt you to enter the text containing the hash value that needs to be repaired.

6. The program will first check for illegal characters (characters other than `a-f` and `0-9`) in the input text. If any illegal characters are found, it will display the number and the list of illegal characters.

7. You will be asked whether you want to delete the illegal characters. If you choose 'Y', the program will remove the illegal characters from the text and display the resulting text.

8. If uppercase characters (`A-F`) are found in the text, the program will display the number and the list of uppercase characters.

9. You will be given two options: delete the uppercase characters or convert them to lowercase.

    - If you choose to delete the uppercase characters, the program will remove them from the text and display the resulting text.
    
    - If you choose to convert the uppercase characters to lowercase, the program will convert them and display the resulting text.

10. The program will terminate after performing the necessary repairs to the hash value.

## Example

Here is an example usage of the **AzaziL-Hash_Fixer-Tool**:

```
Enter the text: 1AbCdEf2

Found 2 uppercase characters: A, C
Do you want to delete them? (Y/N): y
Text after removing uppercase characters: 1bdf2
```
In this example, the input text contains two uppercase characters (`A` and `C`). The user chooses to delete them, and the resulting text is `1bdf2`.

![photo_2023-09-03_03-46-28](https://github.com/MolCoteH/AzaziL_Hash_Fixer/assets/121525098/d6758819-c217-403b-8ae7-779b9f49b607)

## Where to Use

The **AzaziL-Hash_Fixer-Tool** can be used in various scenarios where you encounter damaged or corrupted hash values. Some possible use cases include:

- Data recovery processes where hash values need to be restored.
- Hash verification tasks where the input data may contain illegal or invalid characters.
- Developing tools or scripts that involve hash manipulation or analysis.

Please note that this tool is designed specifically for repairing damaged hash values and may not be suitable for other types of data manipulation or processing.

## Author

AzaziL

## Disclaimer

The **AzaziL-Hash_Fixer-Tool** is provided as-is without any warranty. Use it at your own risk. The author and contributors are not responsible for any damages or losses caused by the use of this tool.
