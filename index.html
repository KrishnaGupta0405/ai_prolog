<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ML Algorithms</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #0d1117;
      --surface: #161b22;
      --border: #30363d;
      --nav-bg: #010409;
      --accent: #58a6ff;
      --accent-dim: #1f6feb;
      --text: #e6edf3;
      --text-muted: #8b949e;
      --green: #3fb950;
      --orange: #d29922;
      --purple: #bc8cff;
      --red: #ff7b72;
      --yellow: #e3b341;
      --code-bg: #161b22;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      line-height: 1.6;
    }

    /* ── Navbar ── */
    nav {
      position: sticky;
      top: 0;
      z-index: 100;
      background: var(--nav-bg);
      border-bottom: 1px solid var(--border);
      display: flex;
      align-items: center;
      gap: 0;
      padding: 0 2rem;
      height: 56px;
      overflow-x: auto;
    }

    nav::-webkit-scrollbar {
      height: 10px;
    }
    nav::-webkit-scrollbar-track {
      background: var(--nav-bg);
    }
    nav::-webkit-scrollbar-thumb {
      background: var(--border);
      border-radius: 4px;
    }
    nav::-webkit-scrollbar-thumb:hover {
      background: var(--text-muted);
    }

    .nav-brand {
      flex-shrink: 0;
      font-weight: 700;
      font-size: 1rem;
      color: var(--text);
      margin-right: 2rem;
      letter-spacing: 0.5px;
    }

    .nav-brand span { color: var(--accent); }

    nav a {
      flex-shrink: 0;
      color: var(--text-muted);
      text-decoration: none;
      font-size: 0.875rem;
      padding: 0 0.85rem;
      height: 56px;
      display: flex;
      align-items: center;
      border-bottom: 2px solid transparent;
      transition: color 0.15s, border-color 0.15s;
      white-space: nowrap;
    }

    nav a:hover { color: var(--text); border-bottom-color: var(--border); }
    nav a.active { color: var(--accent); border-bottom-color: var(--accent); }

    /* ── Layout ── */
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 2.5rem 1.5rem 5rem;
    }

    /* ── Section ── */
    .section {
      margin-bottom: 3.5rem;
      scroll-margin-top: 72px;
    }

    .section-header {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      margin-bottom: 1.5rem;
      padding-bottom: 0.75rem;
      border-bottom: 1px solid var(--border);
    }

    .section-header h2 {
      font-size: 1.35rem;
      font-weight: 600;
      color: var(--text);
    }

    .badge {
      font-size: 0.7rem;
      font-weight: 600;
      padding: 0.2rem 0.55rem;
      border-radius: 20px;
      background: var(--accent-dim);
      color: var(--accent);
      letter-spacing: 0.5px;
      text-transform: uppercase;
    }

    /* ── Dataset table ── */
    .data-table-wrap {
      overflow-x: auto;
      border-radius: 8px;
      border: 1px solid var(--border);
      margin-bottom: 1.5rem;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.875rem;
    }

    th {
      background: var(--surface);
      color: var(--text-muted);
      font-weight: 600;
      text-align: left;
      padding: 0.65rem 1rem;
      border-bottom: 1px solid var(--border);
      letter-spacing: 0.4px;
      font-size: 0.8rem;
      text-transform: uppercase;
    }

    td {
      padding: 0.55rem 1rem;
      border-bottom: 1px solid var(--border);
      color: var(--text);
      font-family: 'SFMono-Regular', Consolas, monospace;
    }

    tr:last-child td { border-bottom: none; }
    tr:hover td { background: rgba(88, 166, 255, 0.04); }

    /* ── Code blocks ── */
    .code-block {
      background: var(--code-bg);
      border: 1px solid var(--border);
      border-radius: 8px;
      overflow: hidden;
      margin-bottom: 1.25rem;
    }

    .code-label {
      background: var(--surface);
      border-bottom: 1px solid var(--border);
      padding: 0.45rem 1rem;
      font-size: 0.75rem;
      color: var(--text-muted);
      font-family: 'SFMono-Regular', Consolas, monospace;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .code-label::before {
      content: '';
      display: inline-block;
      width: 8px; height: 8px;
      border-radius: 50%;
      background: var(--green);
    }

    pre {
      padding: 1.1rem 1.25rem;
      overflow-x: auto;
      font-size: 0.875rem;
      line-height: 1.7;
    }

    code {
      font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', monospace;
    }

    /* Syntax colors */
    .kw  { color: var(--red); }
    .imp { color: var(--purple); }
    .fn  { color: var(--accent); }
    .str { color: var(--yellow); }
    .cm  { color: var(--text-muted); font-style: italic; }
    .num { color: var(--green); }
    .cls { color: var(--orange); }
    .op  { color: var(--text-muted); }
    .var { color: var(--text); }

    /* ── Step cards ── */
    .steps { display: flex; flex-direction: column; gap: 0.85rem; }

    .step {
      display: flex;
      gap: 1rem;
      align-items: flex-start;
    }

    .step-num {
      flex-shrink: 0;
      width: 26px; height: 26px;
      border-radius: 50%;
      background: var(--accent-dim);
      color: var(--accent);
      font-size: 0.75rem;
      font-weight: 700;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 0.15rem;
    }

    .step-body { flex: 1; }

    .step-title {
      font-size: 0.875rem;
      font-weight: 600;
      color: var(--text);
      margin-bottom: 0.35rem;
    }
  
  </style>
</head>
<body>

<!-- ── Navbar ── -->
<nav>
  <div class="nav-brand">ML <span>Notebook</span></div>
  <a href="#simple-linear-regression" class="active">Simple Linear Regression</a>
  <a href="#naive-bayes">Naive Bayes</a>
  <a href="#polynomial-regression">Polynomial Regression</a>
  <a href="#lasso-and-ridge-regression">Lasso and Ridge Regression</a>
  <a href="#logistic-regression">Logistic Regression</a>
  <a href="#artificial-neural-network">Artificial Neural Network</a>
  <a href="#k-nearest-neighbors-k-nn">K-Nearest Neighbors (K-NN)</a>
  <a href="#decision-tree-classification">Decision Tree Classification</a>
  <a href="#support-vector-machine-svm">Support Vector Machine (SVM)</a>
  <a href="#k-means-clustering">K-Means Clustering</a>
  <a href="#hierarchical-clustering">Hierarchical Clustering</a>
</nav>

<!-- ── Content ── -->
<div class="container">

  <!-- Title -->
  <div class="section" id="simple-linear-regression" style="margin-bottom:2rem;">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Simple Linear Regression
    </h1>
    <p style="color:var(--text-muted);font-size:.9rem;">
      Predict salary from years of experience using a single-feature linear model.
    </p>
  </div>

  <!-- Dataset -->
  <div class="section" id="dataset">
    <div class="section-header">
      <h2>Dataset</h2>
      <span class="badge">Salary_Data.csv</span>
    </div>
    <div class="data-table-wrap">
      <table>
        <thead>
          <tr><th>YearsExperience</th><th>Salary</th></tr>
        </thead>
        <tbody>
          <tr><td>1.1</td><td>39343</td></tr>
          <tr><td>1.3</td><td>46205</td></tr>
          <tr><td>1.5</td><td>37731</td></tr>
        </tbody>
      </table>
    </div>
  </div>

  <!-- Libraries -->
  <div class="section" id="libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code><span class="kw">import</span> <span class="var">numpy</span> <span class="kw">as</span> <span class="var">np</span>
<span class="kw">import</span> <span class="var">matplotlib.pyplot</span> <span class="kw">as</span> <span class="var">plt</span>
<span class="kw">import</span> <span class="var">pandas</span> <span class="kw">as</span> <span class="var">pd</span></code></pre>
    </div>
  </div>

  <!-- Load Data -->
  <div class="section" id="load-data">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code><span class="var">dataset</span> <span class="op">=</span> <span class="var">pd</span><span class="op">.</span><span class="fn">read_csv</span><span class="op">(</span><span class="str">'Salary_Data.csv'</span><span class="op">)</span>
<span class="var">X</span> <span class="op">=</span> <span class="var">dataset</span><span class="op">.</span><span class="fn">iloc</span><span class="op">[:,</span> <span class="op">:-</span><span class="num">1</span><span class="op">].</span><span class="fn">values</span>
<span class="var">y</span> <span class="op">=</span> <span class="var">dataset</span><span class="op">.</span><span class="fn">iloc</span><span class="op">[:,</span> <span class="op">-</span><span class="num">1</span><span class="op">].</span><span class="fn">values</span></code></pre>
    </div>
  </div>

  <!-- Split -->
  <div class="section" id="split">
    <div class="section-header"><h2>Splitting the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code><span class="kw">from</span> <span class="var">sklearn.model_selection</span> <span class="kw">import</span> <span class="cls">train_test_split</span>
<span class="var">X_train</span><span class="op">,</span> <span class="var">X_test</span><span class="op">,</span> <span class="var">y_train</span><span class="op">,</span> <span class="var">y_test</span> <span class="op">=</span> <span class="fn">train_test_split</span><span class="op">(</span>
    <span class="var">X</span><span class="op">,</span> <span class="var">y</span><span class="op">,</span> <span class="var">test_size</span><span class="op">=</span><span class="num">1</span><span class="op">/</span><span class="num">3</span><span class="op">,</span> <span class="var">random_state</span><span class="op">=</span><span class="num">0</span>
<span class="op">)</span></code></pre>
    </div>
  </div>

  <!-- Train -->
  <div class="section" id="train">
    <div class="section-header"><h2>Training the model</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code><span class="kw">from</span> <span class="var">sklearn.linear_model</span> <span class="kw">import</span> <span class="cls">LinearRegression</span>
<span class="var">regressor</span> <span class="op">=</span> <span class="cls">LinearRegression</span><span class="op">()</span>
<span class="var">regressor</span><span class="op">.</span><span class="fn">fit</span><span class="op">(</span><span class="var">X_train</span><span class="op">,</span> <span class="var">y_train</span><span class="op">)</span></code></pre>
    </div>
  </div>

  <!-- Predict -->
  <div class="section" id="predict">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code><span class="var">y_pred</span> <span class="op">=</span> <span class="var">regressor</span><span class="op">.</span><span class="fn">predict</span><span class="op">(</span><span class="var">X_test</span><span class="op">)</span></code></pre>
    </div>
  </div>

  <!-- Visualise -->
  <div class="section" id="visualise">
    <div class="section-header"><h2>Visualising the results</h2></div>

    <div class="code-block">
      <div class="code-label">python — Training set</div>
      <pre><code><span class="var">plt</span><span class="op">.</span><span class="fn">scatter</span><span class="op">(</span><span class="var">X_train</span><span class="op">,</span> <span class="var">y_train</span><span class="op">,</span> <span class="var">color</span><span class="op">=</span><span class="str">'red'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">plot</span><span class="op">(</span><span class="var">X_train</span><span class="op">,</span> <span class="var">regressor</span><span class="op">.</span><span class="fn">predict</span><span class="op">(</span><span class="var">X_train</span><span class="op">),</span> <span class="var">color</span><span class="op">=</span><span class="str">'blue'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">title</span><span class="op">(</span><span class="str">'Salary vs Experience (Training set)'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">xlabel</span><span class="op">(</span><span class="str">'Years of Experience'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">ylabel</span><span class="op">(</span><span class="str">'Salary'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">show</span><span class="op">()</span></code></pre>
    </div>

    <div class="code-block">
      <div class="code-label">python — Test set</div>
      <pre><code><span class="var">plt</span><span class="op">.</span><span class="fn">scatter</span><span class="op">(</span><span class="var">X_test</span><span class="op">,</span> <span class="var">y_test</span><span class="op">,</span> <span class="var">color</span><span class="op">=</span><span class="str">'red'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">plot</span><span class="op">(</span><span class="var">X_train</span><span class="op">,</span> <span class="var">regressor</span><span class="op">.</span><span class="fn">predict</span><span class="op">(</span><span class="var">X_train</span><span class="op">),</span> <span class="var">color</span><span class="op">=</span><span class="str">'blue'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">title</span><span class="op">(</span><span class="str">'Salary vs Experience (Test set)'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">xlabel</span><span class="op">(</span><span class="str">'Years of Experience'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">ylabel</span><span class="op">(</span><span class="str">'Salary'</span><span class="op">)</span>
<span class="var">plt</span><span class="op">.</span><span class="fn">show</span><span class="op">()</span></code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Naive Bayes -->
  <!-- ============================================== -->
  <div class="section" id="naive-bayes" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Naive Bayes
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="naive-bayes-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>dataset ->
Age EstimatedSalary Purchased
19 19000 0
35 20000 0</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="naive-bayes-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="naive-bayes-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Social_Network_Ads.csv')
X = dataset.iloc[:, :-1].values
y = dataset.iloc[:, -1].values</code></pre>
    </div>
  </div>


  <!-- Splitting the dataset into the Training set and Test set -->
  <div class="section" id="naive-bayes-splitting-the-dataset-into-the-training-set-and-test-set">
    <div class="section-header"><h2>Splitting the dataset into the Training set and Test set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.25, random_state = 0)

print(X_train)

print(y_train)

print(X_test)

print(y_test)</code></pre>
    </div>
  </div>


  <!-- Feature Scaling -->
  <div class="section" id="naive-bayes-feature-scaling">
    <div class="section-header"><h2>Feature Scaling</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train = sc.fit_transform(X_train)
X_test = sc.transform(X_test)

print(X_train)

print(X_test)</code></pre>
    </div>
  </div>


  <!-- Training the Naive Bayes model on the Training set -->
  <div class="section" id="naive-bayes-training-the-naive-bayes-model-on-the-training-set">
    <div class="section-header"><h2>Training the Naive Bayes model on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.naive_bayes import GaussianNB
classifier = GaussianNB()
classifier.fit(X_train, y_train)</code></pre>
    </div>
  </div>


  <!-- Predicting a new result -->
  <div class="section" id="naive-bayes-predicting-a-new-result">
    <div class="section-header"><h2>Predicting a new result</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>print(classifier.predict(sc.transform([[30,87000]])))</code></pre>
    </div>
  </div>


  <!-- Predicting the Test set results -->
  <div class="section" id="naive-bayes-predicting-the-test-set-results">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>y_pred = classifier.predict(X_test)
print(np.concatenate((y_pred.reshape(len(y_pred),1), y_test.reshape(len(y_test),1)),1))</code></pre>
    </div>
  </div>


  <!-- Making the Confusion Matrix -->
  <div class="section" id="naive-bayes-making-the-confusion-matrix">
    <div class="section-header"><h2>Making the Confusion Matrix</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.metrics import confusion_matrix, accuracy_score
cm = confusion_matrix(y_test, y_pred)
print(cm)
accuracy_score(y_test, y_pred)</code></pre>
    </div>
  </div>


  <!-- Visualising the Training set results -->
  <div class="section" id="naive-bayes-visualising-the-training-set-results">
    <div class="section-header"><h2>Visualising the Training set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_train), y_train
X1, X2 = np.meshgrid(np.arange(start = X_set[:, 0].min() - 10, stop = X_set[:, 0].max() + 10, step = 0.25),
np.arange(start = X_set[:, 1].min() - 1000, stop = X_set[:, 1].max() + 1000, step = 0.25))
plt.contourf(X1, X2, classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape),
alpha = 0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']))
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())
for i, j in enumerate(np.unique(y_set)):
plt.scatter(X_set[y_set == j, 0], X_set[y_set == j, 1], c = ListedColormap(['#FA8072', '#1E90FF'])(i), label = j)
plt.title('Naive Bayes (Training set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Test set results -->
  <div class="section" id="naive-bayes-visualising-the-test-set-results">
    <div class="section-header"><h2>Visualising the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_test), y_test

# Create a grid of points

X1, X2 = np.meshgrid(
np.arange(start=X_set[:, 0].min() - 1, stop=X_set[:, 0].max() + 1, step=0.25),
np.arange(start=X_set[:, 1].min() - 1, stop=X_set[:, 1].max() + 1, step=0.25)
)

# Predict for each point on the grid

Z = classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape)

# Plot the decision boundary

plt.contourf(X1, X2, Z, alpha=0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']) )
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())

# Define colors for scatter plot

colors = ['#FA8072', '#1E90FF']

# Plot the test set points

for i, j in enumerate(np.unique(y_set)):
plt.scatter(
X_set[y_set == j, 0], X_set[y_set == j, 1],
color=colors[i], label=j
)

# Add titles and labels

plt.title('Naive Bayes (Test set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Polynomial Regression -->
  <!-- ============================================== -->
  <div class="section" id="polynomial-regression" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Polynomial Regression
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="polynomial-regression-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>YearsExperience Salary
1.1 39343
1.3 46205
1.5 37731</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="polynomial-regression-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="polynomial-regression-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Position_Salaries.csv')
X = dataset.iloc[:, 1:-1].values
y = dataset.iloc[:, -1].values</code></pre>
    </div>
  </div>


  <!-- Training the Linear Regression model on the whole dataset -->
  <div class="section" id="polynomial-regression-training-the-linear-regression-model-on-the-whole-dataset">
    <div class="section-header"><h2>Training the Linear Regression model on the whole dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.linear_model import LinearRegression
lin_reg = LinearRegression()
lin_reg.fit(X, y)</code></pre>
    </div>
  </div>


  <!-- Training the Polynomial Regression model on the whole dataset -->
  <div class="section" id="polynomial-regression-training-the-polynomial-regression-model-on-the-whole-dataset">
    <div class="section-header"><h2>Training the Polynomial Regression model on the whole dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.preprocessing import PolynomialFeatures
poly_reg = PolynomialFeatures(degree = 4)
X_poly = poly_reg.fit_transform(X)
lin_reg_2 = LinearRegression()
lin_reg_2.fit(X_poly, y)</code></pre>
    </div>
  </div>


  <!-- Visualising the Linear Regression results -->
  <div class="section" id="polynomial-regression-visualising-the-linear-regression-results">
    <div class="section-header"><h2>Visualising the Linear Regression results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>plt.scatter(X, y, color = 'red')
plt.plot(X, lin_reg.predict(X), color = 'blue')
plt.title('Truth or Bluff (Linear Regression)')
plt.xlabel('Position Level')
plt.ylabel('Salary')
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Polynomial Regression results -->
  <div class="section" id="polynomial-regression-visualising-the-polynomial-regression-results">
    <div class="section-header"><h2>Visualising the Polynomial Regression results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>plt.scatter(X, y, color = 'red')
plt.plot(X, lin_reg_2.predict(poly_reg.fit_transform(X)), color = 'blue')
plt.title('Truth or Bluff (Polynomial Regression)')
plt.xlabel('Position level')
plt.ylabel('Salary')
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Polynomial Regression results (for higher resolution and smoother curve) -->
  <div class="section" id="polynomial-regression-visualising-the-polynomial-regression-results-for-higher-resolution-and-smoother-curve">
    <div class="section-header"><h2>Visualising the Polynomial Regression results (for higher resolution and smoother curve)</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>X_grid = np.arange(min(X), max(X), 0.1)
X_grid = X_grid.reshape((len(X_grid), 1))
plt.scatter(X, y, color = 'red')
plt.plot(X_grid, lin_reg_2.predict(poly_reg.fit_transform(X_grid)), color = 'blue')
plt.title('Truth or Bluff (Polynomial Regression)')
plt.xlabel('Position level')
plt.ylabel('Salary')
plt.show()</code></pre>
    </div>
  </div>


  <!-- Predicting a new result with Linear Regression -->
  <div class="section" id="polynomial-regression-predicting-a-new-result-with-linear-regression">
    <div class="section-header"><h2>Predicting a new result with Linear Regression</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>lin_reg.predict([[6.5]])</code></pre>
    </div>
  </div>


  <!-- Predicting a new result with Polynomial Regression -->
  <div class="section" id="polynomial-regression-predicting-a-new-result-with-polynomial-regression">
    <div class="section-header"><h2>Predicting a new result with Polynomial Regression</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>lin_reg_2.predict(poly_reg.fit_transform([[6.5]]))</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Lasso and Ridge Regression -->
  <!-- ============================================== -->
  <div class="section" id="lasso-and-ridge-regression" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Lasso and Ridge Regression
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="lasso-and-ridge-regression-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>YearsExperience Salary
1.1 39343
1.3 46205
1.5 37731</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="lasso-and-ridge-regression-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="lasso-and-ridge-regression-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Salary_Data.csv')
X = dataset.iloc[:, :-1].values
y = dataset.iloc[:, -1].values</code></pre>
    </div>
  </div>


  <!-- Splitting the dataset into the Training set and Test set -->
  <div class="section" id="lasso-and-ridge-regression-splitting-the-dataset-into-the-training-set-and-test-set">
    <div class="section-header"><h2>Splitting the dataset into the Training set and Test set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 1/3, random_state = 0)</code></pre>
    </div>
  </div>


  <!-- Training the Ridge Regression model on the Training set -->
  <div class="section" id="lasso-and-ridge-regression-training-the-ridge-regression-model-on-the-training-set">
    <div class="section-header"><h2>Training the Ridge Regression model on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.linear_model import Ridge
ridge_reg = Ridge(alpha = 1.0)
ridge_reg.fit(X_train, y_train)</code></pre>
    </div>
  </div>


  <!-- Training the Lasso Regression model on the Training set -->
  <div class="section" id="lasso-and-ridge-regression-training-the-lasso-regression-model-on-the-training-set">
    <div class="section-header"><h2>Training the Lasso Regression model on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.linear_model import Lasso
lasso_reg = Lasso(alpha = 0.1)
lasso_reg.fit(X_train, y_train)</code></pre>
    </div>
  </div>


  <!-- Predicting the Test set results -->
  <div class="section" id="lasso-and-ridge-regression-predicting-the-test-set-results">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>y_pred_ridge = ridge_reg.predict(X_test)
y_pred_lasso = lasso_reg.predict(X_test)</code></pre>
    </div>
  </div>


  <!-- Model Evaluation -->
  <div class="section" id="lasso-and-ridge-regression-model-evaluation">
    <div class="section-header"><h2>Model Evaluation</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.metrics import mean_squared_error, r2_score
print('Ridge MSE:', mean_squared_error(y_test, y_pred_ridge))
print('Lasso MSE:', mean_squared_error(y_test, y_pred_lasso))
print('Ridge R²:', r2_score(y_test, y_pred_ridge))
print('Lasso R²:', r2_score(y_test, y_pred_lasso))</code></pre>
    </div>
  </div>


  <!-- Visualising the Ridge Regression results -->
  <div class="section" id="lasso-and-ridge-regression-visualising-the-ridge-regression-results">
    <div class="section-header"><h2>Visualising the Ridge Regression results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>plt.scatter(X_train, y_train, color = 'red', label = 'Training set')
plt.scatter(X_test, y_test, color = 'green', label = 'Test set')
plt.plot(X_train, ridge_reg.predict(X_train), color = 'blue', linewidth = 2)
plt.title('Ridge Regression Results')
plt.xlabel('Years of Experience')
plt.ylabel('Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Lasso Regression results -->
  <div class="section" id="lasso-and-ridge-regression-visualising-the-lasso-regression-results">
    <div class="section-header"><h2>Visualising the Lasso Regression results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>plt.scatter(X_train, y_train, color = 'red', label = 'Training set')
plt.scatter(X_test, y_test, color = 'green', label = 'Test set')
plt.plot(X_train, lasso_reg.predict(X_train), color = 'orange', linewidth = 2)
plt.title('Lasso Regression Results')
plt.xlabel('Years of Experience')
plt.ylabel('Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- Comparing Ridge vs Lasso -->
  <div class="section" id="lasso-and-ridge-regression-comparing-ridge-vs-lasso">
    <div class="section-header"><h2>Comparing Ridge vs Lasso</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>plt.scatter(X_train, y_train, color = 'red', label = 'Training set', alpha = 0.5)
plt.plot(X_train, ridge_reg.predict(X_train), color = 'blue', linewidth = 2, label = 'Ridge')
plt.plot(X_train, lasso_reg.predict(X_train), color = 'orange', linewidth = 2, label = 'Lasso')
plt.title('Ridge vs Lasso Regression')
plt.xlabel('Years of Experience')
plt.ylabel('Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Logistic Regression -->
  <!-- ============================================== -->
  <div class="section" id="logistic-regression" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Logistic Regression
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="logistic-regression-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>Age EstimatedSalary Purchased
19 19000 0
35 20000 0
26 43000 0
27 57000 0
19 76000 0</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="logistic-regression-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="logistic-regression-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Social_Network_Ads.csv')
X = dataset.iloc[:, :-1].values
y = dataset.iloc[:, -1].values</code></pre>
    </div>
  </div>


  <!-- Splitting the dataset into the Training set and Test set -->
  <div class="section" id="logistic-regression-splitting-the-dataset-into-the-training-set-and-test-set">
    <div class="section-header"><h2>Splitting the dataset into the Training set and Test set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.25, random_state = 0)

print(X_train)

print(y_train)

print(X_test)

print(y_test)</code></pre>
    </div>
  </div>


  <!-- Feature Scaling -->
  <div class="section" id="logistic-regression-feature-scaling">
    <div class="section-header"><h2>Feature Scaling</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train = sc.fit_transform(X_train)
X_test = sc.transform(X_test)

print(X_train)

print(X_test)</code></pre>
    </div>
  </div>


  <!-- Training the Logistic Regression model on the Training set -->
  <div class="section" id="logistic-regression-training-the-logistic-regression-model-on-the-training-set">
    <div class="section-header"><h2>Training the Logistic Regression model on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.linear_model import LogisticRegression
classifier = LogisticRegression(random_state = 0)
classifier.fit(X_train, y_train)</code></pre>
    </div>
  </div>


  <!-- Predicting a new result -->
  <div class="section" id="logistic-regression-predicting-a-new-result">
    <div class="section-header"><h2>Predicting a new result</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>print(classifier.predict(sc.transform([[30,87000]])))</code></pre>
    </div>
  </div>


  <!-- Predicting the Test set results -->
  <div class="section" id="logistic-regression-predicting-the-test-set-results">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>y_pred = classifier.predict(X_test)
print(np.concatenate((y_pred.reshape(len(y_pred),1), y_test.reshape(len(y_test),1)),1))</code></pre>
    </div>
  </div>


  <!-- Making the Confusion Matrix -->
  <div class="section" id="logistic-regression-making-the-confusion-matrix">
    <div class="section-header"><h2>Making the Confusion Matrix</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.metrics import confusion_matrix, accuracy_score
cm = confusion_matrix(y_test, y_pred)
print(cm)
accuracy_score(y_test, y_pred)</code></pre>
    </div>
  </div>


  <!-- Visualising the Training set results -->
  <div class="section" id="logistic-regression-visualising-the-training-set-results">
    <div class="section-header"><h2>Visualising the Training set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_train), y_train
X1, X2 = np.meshgrid(np.arange(start = X_set[:, 0].min() - 10, stop = X_set[:, 0].max() + 10, step = 0.25),
np.arange(start = X_set[:, 1].min() - 1000, stop = X_set[:, 1].max() + 1000, step = 0.25))
plt.contourf(X1, X2, classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape),
alpha = 0.75, cmap = ListedColormap(('salmon', 'dodgerblue')))
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())
for i, j in enumerate(np.unique(y_set)):
plt.scatter(X_set[y_set == j, 0], X_set[y_set == j, 1], c = ListedColormap(('salmon', 'dodgerblue'))(i), label = j)
plt.title('Logistic Regression (Training set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Test set results -->
  <div class="section" id="logistic-regression-visualising-the-test-set-results">
    <div class="section-header"><h2>Visualising the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_test), y_test
X1, X2 = np.meshgrid(np.arange(start = X_set[:, 0].min() - 10, stop = X_set[:, 0].max() + 10, step = 0.25),
np.arange(start = X_set[:, 1].min() - 1000, stop = X_set[:, 1].max() + 1000, step = 0.25))
plt.contourf(X1, X2, classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape),
alpha = 0.75, cmap = ListedColormap(('salmon', 'dodgerblue')))
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())
for i, j in enumerate(np.unique(y_set)):
plt.scatter(X_set[y_set == j, 0], X_set[y_set == j, 1], c = ListedColormap(('salmon', 'dodgerblue'))(i), label = j)
plt.title('Logistic Regression (Test set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Artificial Neural Network -->
  <!-- ============================================== -->
  <div class="section" id="artificial-neural-network" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Artificial Neural Network
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="artificial-neural-network-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>RowNumber CustomerId Surname CreditScore Geography Gender Age Tenure Balance NumOfProducts HasCrCard IsActiveMember EstimatedSalary Exited
1 15634602 Hargrave 619 France Female 42 2 0 1 1 1 101348.88 1
2 15647311 Hill 608 Spain Female 41 1 83807.86 1 0 1 112542.58 0
3 15619304 Onio 502 France Female 42 8 159660.8 3 1 0 113931.57 1</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="artificial-neural-network-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import pandas as pd
import tensorflow as tf

tf.__version__</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="artificial-neural-network-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Churn_Modelling.csv')
X = dataset.iloc[:, 3:-1].values
y = dataset.iloc[:, -1].values

print(X)

print(y)</code></pre>
    </div>
  </div>


  <!-- Encoding categorical data -->
  <div class="section" id="artificial-neural-network-encoding-categorical-data">
    <div class="section-header"><h2>Encoding categorical data</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>Label Encoding the "Gender" column

from sklearn.preprocessing import LabelEncoder
le = LabelEncoder()
X[:, 2] = le.fit_transform(X[:, 2])

print(X)

One Hot Encoding the "Geography" column

from sklearn.compose import ColumnTransformer
from sklearn.preprocessing import OneHotEncoder
ct = ColumnTransformer(transformers=[('encoder', OneHotEncoder(), [1])], remainder='passthrough')
X = np.array(ct.fit_transform(X))

print(X)</code></pre>
    </div>
  </div>


  <!-- Splitting the dataset into the Training set and Test set -->
  <div class="section" id="artificial-neural-network-splitting-the-dataset-into-the-training-set-and-test-set">
    <div class="section-header"><h2>Splitting the dataset into the Training set and Test set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.2, random_state = 0)</code></pre>
    </div>
  </div>


  <!-- Feature Scaling -->
  <div class="section" id="artificial-neural-network-feature-scaling">
    <div class="section-header"><h2>Feature Scaling</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train = sc.fit_transform(X_train)
X_test = sc.transform(X_test)</code></pre>
    </div>
  </div>


  <!-- Initializing the ANN -->
  <div class="section" id="artificial-neural-network-initializing-the-ann">
    <div class="section-header"><h2>Initializing the ANN</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>ann = tf.keras.models.Sequential()</code></pre>
    </div>
  </div>


  <!-- Adding the input layer and the first hidden layer -->
  <div class="section" id="artificial-neural-network-adding-the-input-layer-and-the-first-hidden-layer">
    <div class="section-header"><h2>Adding the input layer and the first hidden layer</h2></div>
    <p style="margin-bottom:1rem;color:var(--text-muted);font-size:0.95rem;">ann.add(tf.keras.layers.Dense(units=6, activation='relu'))</p>
  </div>


  <!-- Adding the second hidden layer -->
  <div class="section" id="artificial-neural-network-adding-the-second-hidden-layer">
    <div class="section-header"><h2>Adding the second hidden layer</h2></div>
    <p style="margin-bottom:1rem;color:var(--text-muted);font-size:0.95rem;">ann.add(tf.keras.layers.Dense(units=6, activation='relu'))</p>
  </div>


  <!-- Adding the output layer -->
  <div class="section" id="artificial-neural-network-adding-the-output-layer">
    <div class="section-header"><h2>Adding the output layer</h2></div>
    <p style="margin-bottom:1rem;color:var(--text-muted);font-size:0.95rem;">ann.add(tf.keras.layers.Dense(units=1, activation='sigmoid'))</p>
  </div>


  <!-- Compiling the ANN -->
  <div class="section" id="artificial-neural-network-compiling-the-ann">
    <div class="section-header"><h2>Compiling the ANN</h2></div>
    <p style="margin-bottom:1rem;color:var(--text-muted);font-size:0.95rem;">ann.compile(optimizer = 'adam', loss = 'binary_crossentropy', metrics = ['accuracy'])</p>
  </div>


  <!-- Training the ANN on the Training set -->
  <div class="section" id="artificial-neural-network-training-the-ann-on-the-training-set">
    <div class="section-header"><h2>Training the ANN on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>ann.fit(X_train, y_train, batch_size = 32, epochs = 100)</code></pre>
    </div>
  </div>


  <!-- Predicting the result of a single observation -->
  <div class="section" id="artificial-neural-network-predicting-the-result-of-a-single-observation">
    <div class="section-header"><h2>Predicting the result of a single observation</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>**Homework**

Use our ANN model to predict if the customer with the following informations will leave the bank:

Geography: France

Credit Score: 600

Gender: Male

Age: 40 years old

Tenure: 3 years

Balance: $ 60000

Number of Products: 2

Does this customer have a credit card? Yes

Is this customer an Active Member: Yes

Estimated Salary: $ 50000

So, should we say goodbye to that customer?

**Solution**

print(ann.predict(sc.transform([[1, 0, 0, 600, 1, 40, 3, 60000, 2, 1, 1, 50000]])) > 0.5)

Therefore, our ANN model predicts that this customer stays in the bank!

**Important note 1:** Notice that the values of the features were all input in a double pair of square brackets. That's because the "predict" method always expects a 2D array as the format of its inputs. And putting our values into a double pair of square brackets makes the input exactly a 2D array.

**Important note 2:** Notice also that the "France" country was not input as a string in the last column but as "1, 0, 0" in the first three columns. That's because of course the predict method expects the one-hot-encoded values of the state, and as we see in the first row of the matrix of features X, "France" was encoded as "1, 0, 0". And be careful to include these values in the first three columns, because the dummy variables are always created in the first columns.</code></pre>
    </div>
  </div>


  <!-- Predicting the Test set results -->
  <div class="section" id="artificial-neural-network-predicting-the-test-set-results">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>y_pred = ann.predict(X_test)
y_pred = (y_pred > 0.5)
print(np.concatenate((y_pred.reshape(len(y_pred),1), y_test.reshape(len(y_test),1)),1))</code></pre>
    </div>
  </div>


  <!-- Making the Confusion Matrix -->
  <div class="section" id="artificial-neural-network-making-the-confusion-matrix">
    <div class="section-header"><h2>Making the Confusion Matrix</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.metrics import confusion_matrix, accuracy_score
cm = confusion_matrix(y_test, y_pred)
print(cm)
accuracy_score(y_test, y_pred)</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- K-Nearest Neighbors (K-NN) -->
  <!-- ============================================== -->
  <div class="section" id="k-nearest-neighbors-k-nn" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      K-Nearest Neighbors (K-NN)
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="k-nearest-neighbors-k-nn-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>Age EstimatedSalary Purchased
19 19000 0
35 20000 0
26 43000 0
27 57000 0</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="k-nearest-neighbors-k-nn-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="k-nearest-neighbors-k-nn-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Social_Network_Ads.csv')
X = dataset.iloc[:, :-1].values
y = dataset.iloc[:, -1].values</code></pre>
    </div>
  </div>


  <!-- Splitting the dataset into the Training set and Test set -->
  <div class="section" id="k-nearest-neighbors-k-nn-splitting-the-dataset-into-the-training-set-and-test-set">
    <div class="section-header"><h2>Splitting the dataset into the Training set and Test set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.25, random_state = 0)

print(X_train)

print(y_train)

print(X_test)

print(y_test)</code></pre>
    </div>
  </div>


  <!-- Feature Scaling -->
  <div class="section" id="k-nearest-neighbors-k-nn-feature-scaling">
    <div class="section-header"><h2>Feature Scaling</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train = sc.fit_transform(X_train)
X_test = sc.transform(X_test)

print(X_train)

print(X_test)</code></pre>
    </div>
  </div>


  <!-- Training the K-NN model on the Training set -->
  <div class="section" id="k-nearest-neighbors-k-nn-training-the-k-nn-model-on-the-training-set">
    <div class="section-header"><h2>Training the K-NN model on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.neighbors import KNeighborsClassifier
classifier = KNeighborsClassifier(n_neighbors = 5, metric = 'minkowski', p = 2)
classifier.fit(X_train, y_train)</code></pre>
    </div>
  </div>


  <!-- Predicting a new result -->
  <div class="section" id="k-nearest-neighbors-k-nn-predicting-a-new-result">
    <div class="section-header"><h2>Predicting a new result</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>print(classifier.predict(sc.transform([[30,87000]])))</code></pre>
    </div>
  </div>


  <!-- Predicting the Test set results -->
  <div class="section" id="k-nearest-neighbors-k-nn-predicting-the-test-set-results">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>y_pred = classifier.predict(X_test)
print(np.concatenate((y_pred.reshape(len(y_pred),1), y_test.reshape(len(y_test),1)),1))</code></pre>
    </div>
  </div>


  <!-- Making the Confusion Matrix -->
  <div class="section" id="k-nearest-neighbors-k-nn-making-the-confusion-matrix">
    <div class="section-header"><h2>Making the Confusion Matrix</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.metrics import confusion_matrix, accuracy_score
cm = confusion_matrix(y_test, y_pred)
print(cm)
accuracy_score(y_test, y_pred)</code></pre>
    </div>
  </div>


  <!-- Visualising the Training set results -->
  <div class="section" id="k-nearest-neighbors-k-nn-visualising-the-training-set-results">
    <div class="section-header"><h2>Visualising the Training set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_train), y_train
X1, X2 = np.meshgrid(np.arange(start = X_set[:, 0].min() - 10, stop = X_set[:, 0].max() + 10, step = 0.5),
np.arange(start = X_set[:, 1].min() - 1000, stop = X_set[:, 1].max() + 1000, step = 0.5))
plt.contourf(X1, X2, classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape),
alpha = 0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']))
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())
for i, j in enumerate(np.unique(y_set)):
plt.scatter(X_set[y_set == j, 0], X_set[y_set == j, 1], c = ListedColormap(['#FA8072', '#1E90FF'])(i), label = j)
plt.title('K-NN (Training set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Test set results -->
  <div class="section" id="k-nearest-neighbors-k-nn-visualising-the-test-set-results">
    <div class="section-header"><h2>Visualising the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_test), y_test

# Create a grid of points

X1, X2 = np.meshgrid(
np.arange(start=X_set[:, 0].min() - 1, stop=X_set[:, 0].max() + 1, step=0.5),
np.arange(start=X_set[:, 1].min() - 1, stop=X_set[:, 1].max() + 1, step=0.5)
)

# Predict for each point on the grid

Z = classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape)

# Plot the decision boundary

plt.contourf(X1, X2, Z, alpha=0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']) )
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())

# Define colors for scatter plot

colors = ['#FA8072', '#1E90FF']

# Plot the test set points

for i, j in enumerate(np.unique(y_set)):
plt.scatter(
X_set[y_set == j, 0], X_set[y_set == j, 1],
color=colors[i], label=j
)

# Add titles and labels

plt.title('K-NN (Test set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Decision Tree Classification -->
  <!-- ============================================== -->
  <div class="section" id="decision-tree-classification" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Decision Tree Classification
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="decision-tree-classification-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>Age EstimatedSalary Purchased
19 19000 0
35 20000 0
26 43000 0
27 57000 0</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="decision-tree-classification-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="decision-tree-classification-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Social_Network_Ads.csv')
X = dataset.iloc[:, :-1].values
y = dataset.iloc[:, -1].values</code></pre>
    </div>
  </div>


  <!-- Splitting the dataset into the Training set and Test set -->
  <div class="section" id="decision-tree-classification-splitting-the-dataset-into-the-training-set-and-test-set">
    <div class="section-header"><h2>Splitting the dataset into the Training set and Test set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.25, random_state = 0)

print(X_train)

print(y_train)

print(X_test)

print(y_test)</code></pre>
    </div>
  </div>


  <!-- Feature Scaling -->
  <div class="section" id="decision-tree-classification-feature-scaling">
    <div class="section-header"><h2>Feature Scaling</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train = sc.fit_transform(X_train)
X_test = sc.transform(X_test)

print(X_train)

print(X_test)</code></pre>
    </div>
  </div>


  <!-- Training the Decision Tree Classification model on the Training set -->
  <div class="section" id="decision-tree-classification-training-the-decision-tree-classification-model-on-the-training-set">
    <div class="section-header"><h2>Training the Decision Tree Classification model on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.tree import DecisionTreeClassifier
classifier = DecisionTreeClassifier(criterion = 'entropy', random_state = 0)
classifier.fit(X_train, y_train)</code></pre>
    </div>
  </div>


  <!-- Predicting a new result -->
  <div class="section" id="decision-tree-classification-predicting-a-new-result">
    <div class="section-header"><h2>Predicting a new result</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>print(classifier.predict(sc.transform([[30,87000]])))</code></pre>
    </div>
  </div>


  <!-- Predicting the Test set results -->
  <div class="section" id="decision-tree-classification-predicting-the-test-set-results">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>y_pred = classifier.predict(X_test)
print(np.concatenate((y_pred.reshape(len(y_pred),1), y_test.reshape(len(y_test),1)),1))</code></pre>
    </div>
  </div>


  <!-- Making the Confusion Matrix -->
  <div class="section" id="decision-tree-classification-making-the-confusion-matrix">
    <div class="section-header"><h2>Making the Confusion Matrix</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.metrics import confusion_matrix, accuracy_score
cm = confusion_matrix(y_test, y_pred)
print(cm)
accuracy_score(y_test, y_pred)</code></pre>
    </div>
  </div>


  <!-- Visualising the Training set results -->
  <div class="section" id="decision-tree-classification-visualising-the-training-set-results">
    <div class="section-header"><h2>Visualising the Training set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_train), y_train
X1, X2 = np.meshgrid(np.arange(start = X_set[:, 0].min() - 10, stop = X_set[:, 0].max() + 10, step = 0.25),
np.arange(start = X_set[:, 1].min() - 1000, stop = X_set[:, 1].max() + 1000, step = 0.25))
plt.contourf(X1, X2, classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape),
alpha = 0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']))
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())
for i, j in enumerate(np.unique(y_set)):
plt.scatter(X_set[y_set == j, 0], X_set[y_set == j, 1], c = ListedColormap(['#FA8072', '#1E90FF'])(i), label = j)
plt.title('Decision Tree Classifier (Training set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Test set results -->
  <div class="section" id="decision-tree-classification-visualising-the-test-set-results">
    <div class="section-header"><h2>Visualising the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_test), y_test

# Create a grid of points

X1, X2 = np.meshgrid(
np.arange(start=X_set[:, 0].min() - 1, stop=X_set[:, 0].max() + 1, step=0.25),
np.arange(start=X_set[:, 1].min() - 1, stop=X_set[:, 1].max() + 1, step=0.25)
)

# Predict for each point on the grid

Z = classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape)

# Plot the decision boundary

plt.contourf(X1, X2, Z, alpha=0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']) )
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())

# Define colors for scatter plot

colors = ['#FA8072', '#1E90FF']

# Plot the test set points

for i, j in enumerate(np.unique(y_set)):
plt.scatter(
X_set[y_set == j, 0], X_set[y_set == j, 1],
color=colors[i], label=j
)

# Add titles and labels

plt.title('Decision Tree Classifier (Test set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Support Vector Machine (SVM) -->
  <!-- ============================================== -->
  <div class="section" id="support-vector-machine-svm" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Support Vector Machine (SVM)
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="support-vector-machine-svm-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>Age EstimatedSalary Purchased
19 19000 0
35 20000 0
26 43000 0</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="support-vector-machine-svm-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="support-vector-machine-svm-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Social_Network_Ads.csv')
X = dataset.iloc[:, :-1].values
y = dataset.iloc[:, -1].values</code></pre>
    </div>
  </div>


  <!-- Splitting the dataset into the Training set and Test set -->
  <div class="section" id="support-vector-machine-svm-splitting-the-dataset-into-the-training-set-and-test-set">
    <div class="section-header"><h2>Splitting the dataset into the Training set and Test set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size = 0.25, random_state = 0)

print(X_train)

print(y_train)

print(X_test)

print(y_test)</code></pre>
    </div>
  </div>


  <!-- Feature Scaling -->
  <div class="section" id="support-vector-machine-svm-feature-scaling">
    <div class="section-header"><h2>Feature Scaling</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train = sc.fit_transform(X_train)
X_test = sc.transform(X_test)

print(X_train)

print(X_test)</code></pre>
    </div>
  </div>


  <!-- Training the SVM model on the Training set -->
  <div class="section" id="support-vector-machine-svm-training-the-svm-model-on-the-training-set">
    <div class="section-header"><h2>Training the SVM model on the Training set</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.svm import SVC
classifier = SVC(kernel = 'linear', random_state = 0)
classifier.fit(X_train, y_train)</code></pre>
    </div>
  </div>


  <!-- Predicting a new result -->
  <div class="section" id="support-vector-machine-svm-predicting-a-new-result">
    <div class="section-header"><h2>Predicting a new result</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>print(classifier.predict(sc.transform([[30,87000]])))</code></pre>
    </div>
  </div>


  <!-- Predicting the Test set results -->
  <div class="section" id="support-vector-machine-svm-predicting-the-test-set-results">
    <div class="section-header"><h2>Predicting the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>y_pred = classifier.predict(X_test)
print(np.concatenate((y_pred.reshape(len(y_pred),1), y_test.reshape(len(y_test),1)),1))</code></pre>
    </div>
  </div>


  <!-- Making the Confusion Matrix -->
  <div class="section" id="support-vector-machine-svm-making-the-confusion-matrix">
    <div class="section-header"><h2>Making the Confusion Matrix</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.metrics import confusion_matrix, accuracy_score
cm = confusion_matrix(y_test, y_pred)
print(cm)
accuracy_score(y_test, y_pred)</code></pre>
    </div>
  </div>


  <!-- Visualising the Training set results -->
  <div class="section" id="support-vector-machine-svm-visualising-the-training-set-results">
    <div class="section-header"><h2>Visualising the Training set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_train), y_train
X1, X2 = np.meshgrid(np.arange(start = X_set[:, 0].min() - 10, stop = X_set[:, 0].max() + 10, step = 0.25),
np.arange(start = X_set[:, 1].min() - 1000, stop = X_set[:, 1].max() + 1000, step = 0.25))
plt.contourf(X1, X2, classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape),
alpha = 0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']))
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())
for i, j in enumerate(np.unique(y_set)):
plt.scatter(X_set[y_set == j, 0], X_set[y_set == j, 1], c = ListedColormap(['#FA8072', '#1E90FF'])(i), label = j)
plt.title('SVM (Training set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- Visualising the Test set results -->
  <div class="section" id="support-vector-machine-svm-visualising-the-test-set-results">
    <div class="section-header"><h2>Visualising the Test set results</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from matplotlib.colors import ListedColormap
X_set, y_set = sc.inverse_transform(X_test), y_test

# Create a grid of points

X1, X2 = np.meshgrid(
np.arange(start=X_set[:, 0].min() - 1, stop=X_set[:, 0].max() + 1, step=0.25),
np.arange(start=X_set[:, 1].min() - 1, stop=X_set[:, 1].max() + 1, step=0.25)
)

# Predict for each point on the grid

Z = classifier.predict(sc.transform(np.array([X1.ravel(), X2.ravel()]).T)).reshape(X1.shape)

# Plot the decision boundary

plt.contourf(X1, X2, Z, alpha=0.75, cmap = ListedColormap(['#FA8072', '#1E90FF']) )
plt.xlim(X1.min(), X1.max())
plt.ylim(X2.min(), X2.max())

# Define colors for scatter plot

colors = ['#FA8072', '#1E90FF']

# Plot the test set points

for i, j in enumerate(np.unique(y_set)):
plt.scatter(
X_set[y_set == j, 0], X_set[y_set == j, 1],
color=colors[i], label=j
)

# Add titles and labels

plt.title('SVM (Test set)')
plt.xlabel('Age')
plt.ylabel('Estimated Salary')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- K-Means Clustering -->
  <!-- ============================================== -->
  <div class="section" id="k-means-clustering" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      K-Means Clustering
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="k-means-clustering-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>CustomerID Genre Age Annual Income (k$) Spending Score (1-100)
1 Male 19 15 39
2 Male 21 15 81
3 Female 20 16 6</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="k-means-clustering-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="k-means-clustering-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Mall_Customers.csv')
X = dataset.iloc[:, [3, 4]].values</code></pre>
    </div>
  </div>


  <!-- Using the elbow method to find the optimal number of clusters -->
  <div class="section" id="k-means-clustering-using-the-elbow-method-to-find-the-optimal-number-of-clusters">
    <div class="section-header"><h2>Using the elbow method to find the optimal number of clusters</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.cluster import KMeans
wcss = []
for i in range(1, 11):
kmeans = KMeans(n_clusters = i, init = 'k-means++', random_state = 42)
kmeans.fit(X)
wcss.append(kmeans.inertia_)
plt.plot(range(1, 11), wcss)
plt.title('The Elbow Method')
plt.xlabel('Number of clusters')
plt.ylabel('WCSS')
plt.show()</code></pre>
    </div>
  </div>


  <!-- Training the K-Means model on the dataset -->
  <div class="section" id="k-means-clustering-training-the-k-means-model-on-the-dataset">
    <div class="section-header"><h2>Training the K-Means model on the dataset</h2></div>
    <p style="margin-bottom:1rem;color:var(--text-muted);font-size:0.95rem;">kmeans = KMeans(n_clusters = 5, init = 'k-means++', random_state = 42)<br/>y_kmeans = kmeans.fit_predict(X)</p>
  </div>


  <!-- Visualising the clusters -->
  <div class="section" id="k-means-clustering-visualising-the-clusters">
    <div class="section-header"><h2>Visualising the clusters</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>plt.scatter(X[y_kmeans == 0, 0], X[y_kmeans == 0, 1], s = 100, c = 'red', label = 'Cluster 1')
plt.scatter(X[y_kmeans == 1, 0], X[y_kmeans == 1, 1], s = 100, c = 'blue', label = 'Cluster 2')
plt.scatter(X[y_kmeans == 2, 0], X[y_kmeans == 2, 1], s = 100, c = 'green', label = 'Cluster 3')
plt.scatter(X[y_kmeans == 3, 0], X[y_kmeans == 3, 1], s = 100, c = 'cyan', label = 'Cluster 4')
plt.scatter(X[y_kmeans == 4, 0], X[y_kmeans == 4, 1], s = 100, c = 'magenta', label = 'Cluster 5')
plt.scatter(kmeans.cluster_centers_[:, 0], kmeans.cluster_centers_[:, 1], s = 300, c = 'yellow', label = 'Centroids')
plt.title('Clusters of customers')
plt.xlabel('Annual Income (k$)')
plt.ylabel('Spending Score (1-100)')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>


  <!-- ============================================== -->
  <!-- Hierarchical Clustering -->
  <!-- ============================================== -->
  <div class="section" id="hierarchical-clustering" style="margin-bottom:2rem; padding-top:3rem; margin-top:2rem; border-top:1px solid var(--border);">
    <h1 style="font-size:1.75rem;font-weight:700;color:var(--text);margin-bottom:.4rem;">
      Hierarchical Clustering
    </h1>
  </div>


  <!-- Dataset -->
  <div class="section" id="hierarchical-clustering-dataset">
    <div class="section-header">
      <h2>Dataset</h2>
    </div>
    <div class="code-block">
      <pre style="background: var(--surface);"><code>CustomerID Genre Age Annual Income (k$) Spending Score (1-100)
1 Male 19 15 39
2 Male 21 15 81
3 Female 20 16 6
4 Female 23 16 77
5 Female 31 17 40</code></pre>
    </div>
  </div>


  <!-- Importing the libraries -->
  <div class="section" id="hierarchical-clustering-importing-the-libraries">
    <div class="section-header"><h2>Importing the libraries</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import numpy as np
import matplotlib.pyplot as plt
import pandas as pd</code></pre>
    </div>
  </div>


  <!-- Importing the dataset -->
  <div class="section" id="hierarchical-clustering-importing-the-dataset">
    <div class="section-header"><h2>Importing the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>dataset = pd.read_csv('Mall_Customers.csv')
X = dataset.iloc[:, [3, 4]].values</code></pre>
    </div>
  </div>


  <!-- Using the dendrogram to find the optimal number of clusters -->
  <div class="section" id="hierarchical-clustering-using-the-dendrogram-to-find-the-optimal-number-of-clusters">
    <div class="section-header"><h2>Using the dendrogram to find the optimal number of clusters</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>import scipy.cluster.hierarchy as sch
dendrogram = sch.dendrogram(sch.linkage(X, method = 'ward'))
plt.title('Dendrogram')
plt.xlabel('Customers')
plt.ylabel('Euclidean distances')
plt.show()</code></pre>
    </div>
  </div>


  <!-- Training the Hierarchical Clustering model on the dataset -->
  <div class="section" id="hierarchical-clustering-training-the-hierarchical-clustering-model-on-the-dataset">
    <div class="section-header"><h2>Training the Hierarchical Clustering model on the dataset</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>from sklearn.cluster import AgglomerativeClustering
hc = AgglomerativeClustering(n_clusters = 5, affinity = 'euclidean', linkage = 'ward')
y_hc = hc.fit_predict(X)</code></pre>
    </div>
  </div>


  <!-- Visualising the clusters -->
  <div class="section" id="hierarchical-clustering-visualising-the-clusters">
    <div class="section-header"><h2>Visualising the clusters</h2></div>
    <div class="code-block">
      <div class="code-label">python</div>
      <pre><code>plt.scatter(X[y_hc == 0, 0], X[y_hc == 0, 1], s = 100, c = 'red', label = 'Cluster 1')
plt.scatter(X[y_hc == 1, 0], X[y_hc == 1, 1], s = 100, c = 'blue', label = 'Cluster 2')
plt.scatter(X[y_hc == 2, 0], X[y_hc == 2, 1], s = 100, c = 'green', label = 'Cluster 3')
plt.scatter(X[y_hc == 3, 0], X[y_hc == 3, 1], s = 100, c = 'cyan', label = 'Cluster 4')
plt.scatter(X[y_hc == 4, 0], X[y_hc == 4, 1], s = 100, c = 'magenta', label = 'Cluster 5')
plt.title('Clusters of customers')
plt.xlabel('Annual Income (k$)')
plt.ylabel('Spending Score (1-100)')
plt.legend()
plt.show()</code></pre>
    </div>
  </div>

</div>

<script>
  // Highlight active nav link on scroll
  const sections = document.querySelectorAll('.section[id]');
  const links = document.querySelectorAll('nav a[href^="#"]');

  const observer = new IntersectionObserver(entries => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        links.forEach(l => l.classList.remove('active'));
        const active = document.querySelector(`nav a[href="#${e.target.id}"]`);
        if (active) active.classList.add('active');
      }
    });
  }, { rootMargin: '-20% 0px -70% 0px' });

  sections.forEach(s => observer.observe(s));
</script>

</body>
</html>
