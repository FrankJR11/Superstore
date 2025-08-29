# This cell loads the Superstore dataset and performs initial inspection
import pandas as pd

file_path = r"C:\Users\FrankJR\Downloads\Portfolio\Superstore Dataset\Sample - Superstore.csv"

# Read with provided encoding
superstore_df = pd.read_csv(file_path, encoding='ISO-8859-1')

print('Loaded rows: ' + str(superstore_df.shape[0]))
print('Loaded columns: ' + str(superstore_df.shape[1]))
print('Columns: ' + ', '.join(list(superstore_df.columns)))

# Show head
print('Head:')
print(superstore_df.head(5))

# Basic summary stats for numeric columns
print('Describe numeric:')
print(superstore_df.describe(include='number'))

# Convert order and ship dates to datetime for later analysis
superstore_df['Order_Date'] = pd.to_datetime(superstore_df[' Order_Date'], dayfirst=False, errors='coerce', infer_datetime_format=True)
superstore_df['Ship_Date'] = pd.to_datetime(superstore_df[' Ship_Date'], dayfirst=False, errors='coerce', infer_datetime_format=True)

# Strip column names of whitespace
superstore_df.columns = [c.strip() for c in superstore_df.columns]

print('Post-clean Columns: ' + ', '.join(list(superstore_df.columns)))
print('Post-clean Head:')
print(superstore_df.head(3))
