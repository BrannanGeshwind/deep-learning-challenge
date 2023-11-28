# deep-learning-challenge
Module 21 Challenge

## Notes:
-----
Added the Notebooks for the optimizations as well as the .h5 files. Credit to Nathan Humphreys Lucas for this line of code that was a correction to what I had written:

#Export our model to HDF5 file <br>
#Documentation: https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_hdf.html <br>
results_df = pd.DataFrame({'Loss':[model_loss], 'Accuracy':[model_accuracy]}) <br>
results_df.head() <br>
results_df.to_hdf(r'AlphabetSoupCharity.h5',\ <br>
                    key = 'results_df',\ <br>
                    mode='w') <br>

## Updates:
-----
- 11/27 - Finished code. Updating README for submission.
- 11/16 - Tested optimizations in Google Collaboratory.
- 11/8 - Created repo and pushed starter files.

## Languages and References:
-----
- [Python](https://docs.python.org/3/)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/)
- [Pandas](https://pandas.pydata.org/docs/)
- [StackOverflow](https://stackoverflow.com/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [TensorFlow](https://github.com/tensorflow/docs)
