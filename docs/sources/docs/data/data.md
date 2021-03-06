# Minmax Scaling
	def minmax_scaling(df, columns, min_val=0, max_val=1):
	    """
	    Min max scaling for pandas DataFrames

	    Parameters
	    ----------
	    df : pandas DataFrame object.

	    columns : array-like, shape = [n_columns]
	      Array-like with pandas DataFrame column names, e.g., ['col1', 'col2', ...]

	    min_val : `int` or `float`, optional (default=`0`)
	      minimum value after rescaling.

	    min_val : `int` or `float`, optional (default=`1`)
	      maximum value after rescaling.

	    Returns
	    ----------

	    df_new: pandas DataFrame object.
	      Copy of the DataFrame with rescaled columns.

	    """

# Standardizing

	def standardizing(df, columns):
	    """
	    Standardizing columns in pandas DataFrames.

	    Parameters
	    ----------
	    df : pandas DataFrame object.

	    columns : array-like, shape = [n_columns]
	      Array-like with pandas DataFrame column names, e.g., ['col1', 'col2', ...]

	    Returns
	    ----------

	    df_new: pandas DataFrame object.
	      Copy of the DataFrame with standardized columns.

	    """