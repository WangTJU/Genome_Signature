
This is a guide to encoding and decoding Genome Signatures using the demo program for windows.
 
File preparation:
1. If you want to encode Genome Signature, please refer to the encode.json file format in the data folder. Where "orf" is the gene sequence to be encoded, and "upstream" is the genomic sequence between the current gene to be encoded and the upstream gene to be encoded. 
2. If you want to decode Genome Signature, please refer to encode_result.json file format in data folder (encode output file can be decoded directly). where "gene_loop" is the genome sequence to be decoded.

program execution:
1. command: ............\Genome_Signature\Release_x64> .\WGUEC.exe ..\WGUEC-params.json
2. params in WGUEC-params.json: "function"(Execution status: 0=off, 1=on). For example, to perform encoding, adjust the number after "ENCODE" to "1".
3. Encoding Result: after the "ENCODE" program is executed, the latest output_path.txt, encode_result.json file appears in the output folder; 
4. Decoding Result: after the "DECODE" program is executed,  the latest output_path.txt, decode_result.json file appears in the output folder.

We also welcome registration and login https://genomemory.org/ to use the demo program.

This software is expressly prohibited from commercial use. 
All rights are reserved for academic research and non-profit applications only. 
Any commercialization, including but not limited to incorporation into commercial products, resale, or fee-based services, requires prior written authorization from the copyright holders.




