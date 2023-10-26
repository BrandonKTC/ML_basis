# Feature Engineering:
Is the process of using domain knowledge to extract features from raw data via data mining techniques.
- really understand what the rows/columns correspond to in the dataset and what's important in it
- Data mining
* transform feature into a numeric feature set
* break down information that can be within a data feature
## 3 general approaches:
- Extracting Information
- Combining Information
- Transforming Information

### One Hot Encoding (Dummy Variables)
Convert categories into individual feaatures that are either 0 or 1
- Pros:
no ordering implied.
- Cons:
* Potential to create many more feature columns and coefficients.
* Dummy variable trap consideration.
* Not easy to add new categories.

Dropping the feature column:
* easy to do.
* potential to lose a feature with possible important signal.
* Should consider drop feature approach when many rows are NAN.

Filling in missing feature data:
* Potentially changing ground truth in data.
* Must decide on reasonable estimation to filled value.
* Must apply transformation to all future data for predictions.
 
