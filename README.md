# AES-Cryptographic-Tool
Designed and implemented a File Encryption and Decryption Tool in Python, leveraging XOR-based encryption for data security. The tool provides a seamless and user-friendly experience, featuring a distinctive logo for each operation using the termcolor and tqdm libraries. The program begins with a menu offering encryption, decryption, or exit options, providing a clear and intuitive interface.

For the encryption process, the user inputs the filename for encryption with the proper extension. The tool then opens the file, reads its content, and performs byte-wise XOR operations with a predefined key (192). The encrypted content is written to a new file prefixed with 'cipher_'. The decryption process similarly prompts the user to enter the encrypted filename, performs XOR operations, and writes the decrypted content to a new file. Both processes are augmented with tqdm for progress visualization.

Exception handling is implemented to address potential issues like file not found or general exceptions during the encryption or decryption processes. The tool efficiently handles errors, providing informative messages to the user.

The tool features an engaging visual layout with a logo representing the encryption or decryption operation, enhancing the user experience. After each successful encryption or decryption, the user is prompted to continue or exit, allowing for multiple operations in one session.

This project highlights proficiency in cryptography, file handling, and user interaction design. The integration of encryption techniques showcases a commitment to data security, while the user-friendly interface and informative messages demonstrate a thoughtful approach to user experience. The inclusion of tqdm for progress tracking adds an extra layer of transparency to the processes, reflecting attention to detail and effective communication in the design of the tool.
