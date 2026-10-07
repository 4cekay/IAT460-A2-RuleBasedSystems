# IAT460-A2-RuleBasedSystems

"Haiku Tree Generator"

How to run project (Colab):

1. Make sure to run all cells in "Setup" to install/import requirements + colour map
  
2. Run the code cells in "Generative Grammar System" to:
  - Define helper functions and the grammar system.
    - Vocabulary can be customized by changing the word strings in the individual part of speech keys within the "haiku_grammar" dict.
    - When customizing vocabulary, words MUST be added to the correct syllable count per part of speech.
    - For example: "brilliantly" would be added to the list value of key 'ADV_S4'
  - Generate the a haiku using the available vocabulary, receiving a dict item with the new poem and its metadata.

3. Run the code cells in "L-System" to:
   - Define helper functions.
   - Map the poem in instructions for Turtle Graphics to follow, then generate an instructions string.
   - Use the drawing function to generate your haiku's fractal tree. Customize the "angle" and "distance" parameters if needed (to avoid out-of-bounds drawing)
