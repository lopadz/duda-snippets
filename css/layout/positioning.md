# Positioning

## Center content vertically
Vertically center content inside a column.

**Type**: Inline

**Usage**:
1. Create a row with 2 columns
2. Add an inner row with one column to the column you want to center content in
3. Add the following CSS to the parent column (not the column inside the inner row):
```
align-items: center;
display: flex;
```