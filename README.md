# personal-notes-on-file-system-presentations-hannesfuereder




Nico: 
Block with all addresses of the fileHead Block 
Create: Always 3 Blocks
Increase: They don’t have a list with all free places (they search)	
Seek: Get Parameter to jump to the specific place
Remove: just free the blocks

Danninger:
Description Block
Content Block
Free Block Table
Sub Desc Block
Seek: Calculate and jump to the specific point

Thomas:
Blocks are all linked together 
Read: iterate (jump from block to block)
Seek: iterate through all blocks

Paul
Seek: Calculate and jump to the specific point
Directory Block: Store addresses of what’s in it (Files, other directory Blocks)

Janine
Linked list
Seek: Calculate and jump to the specific point
Similarities:
Create: Search in the Free Block Table and fill necessary Blocks
Read: Iterate over the Block with all addresses 
Remove: Add Block to Free Block Table
Increase: Take Blocks from the Free Block Table and add them.
Delete File: all addresses in the Desc. Block to Free Block Table
Seek: SpecifiedSize/BlockSize = index -> Block to go

