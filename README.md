<h1>Signal Processing</h1>
<h3>Code and resources for noise reduction from signals</h3>


This folder contains code for filtering both csv type files(spreadsheet), and wav type files(audio) for removing noise from the given file.
I figured out the output is different, when the x-y graph scales are
1.  equal in all outputs,(like y = -3-5 and -3-5 and -3-5)
2. and unequal in all outputs(like y = -3-5 and 6-11 and 0-22)

So, I created code for both cases, so basically 4 modules of code, in the *main.ipynb* file. 

OUTPUT--->>>In *adaptive_filtered_signal.wav* and *cleaned_seismic_signal.csv* and *cleaned_signal.csv*, *cleaned_seismic_signal.csv* are the outputs generated, when the modules are run. Each time the modules overwrite the previous content in the output files.

INPUT --->>>*assets_etcetc.wav* is the sample signal+noise audio I tested the code with.(I ran 6 wav->csv+wav tests in total)  <br>
[_credits to Tim Sainburg's sample files "https://github.com/timsainb/noisereduce?tab=readme-ov-file#usage"_]

INPUT --->>>*hahatest1.csv* is the sample signal+noise doc I tested with.(I ran 12 csv->wav+csv tests in total) <br>
[_credits to nasa's ridiculously complex-to-navigate databases."https://pds-geosciences.wustl.edu/lunar/"_]
