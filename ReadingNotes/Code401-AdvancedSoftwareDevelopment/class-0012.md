# Pandas Functions

## Object creation
    - Creating a Series by passing a list of values
        s = pd.Series([1, 3, 5, np.nan, 6, 8])

    - Creating a DataFrame by passing a NumPy array
        dates = pd.date_range("20130101", periods=6)

## Viewing data
    -   df.head()
    -   df.index
    -   df.describe()
    -   df.sort_index(axis=1, ascending=False)
    -   df.sort_values(by="B")

## Selection
    - df["A"] -> Selecting a single column, which yields a Series, equivalent to df.A
    - df[0:3] -> Selecting via [], which slices the rows

## Selection by label
    - df.loc[dates[0]] -> For getting a cross section using a label
    - df.loc[:, ["A", "B"]] -> Selecting on a multi-axis by label
    
