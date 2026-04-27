# macOS Math & ML/DL Text Shortcuts

> Instantly type math symbols, Greek letters, and deep learning notation on macOS — no LaTeX, no copy-paste.

Type `;alpha` → get `α`. Type `;attention` → get `Attention(Q,K,V) = softmax(QKᵀ/√dₖ)V`.

---

## What's included

| Category | Count | Examples |
|---|---|---|
| Greek letters (lower) | 23 | `;alpha` → α, `;theta` → θ, `;lambda` → λ |
| Greek letters (upper) | 11 | `;Sigma` → Σ, `;Delta` → Δ, `;Phi` → Φ |
| Calculus & analysis | 9 | `;grad` → ∇, `;partial` → ∂, `;int` → ∫ |
| Linear algebra | 13 | `;norm` → ‖, `;otimes` → ⊗, `;T` → ⊤ |
| Probability & stats | 17 | `;E` → 𝔼, `;P` → ℙ, `;Normal` → 𝒩(μ,σ²) |
| Set theory & logic | 13 | `;in` → ∈, `;forall` → ∀, `;union` → ∪ |
| Number sets | 5 | `;R` → ℝ, `;Z` → ℤ, `;N` → ℕ |
| Comparisons & relations | 10 | `;leq` → ≤, `;approx` → ≈, `;defeq` → ≜ |
| Arrows | 10 | `;to` → →, `;iff` → ⇔, `;mapsto` → ↦ |
| Deep learning — activations | 8 | `;relu`, `;sigmoid`, `;softmax` |
| Deep learning — loss functions | 5 | `;mse`, `;crossentropy`, `;bce` |
| Deep learning — optimisation | 7 | `;sgd`, `;adamupdate`, `;dloss` |
| Transformers & attention | 4 | `;attention`, `;multihead`, `;posenc` |
| Machine learning — general | 17 | `;yhat` → ŷ, `;dataset`, `;dtrain` |
| Reinforcement learning | 7 | `;valuefn`, `;policy`, `;advantage` |
| Information theory | 4 | `;entropy`, `;kldiv`, `;mutualinfo` |
| Superscripts & subscripts | 15 | `;inv` → ⁻¹, `;subt` → ₜ, `;sup2` → ² |
| Misc math | 16 | `;sqrt` → √, `;ldots` → …, `;floor` → ⌊ |

**Total: ~130 shortcuts**

---

## Full shortcut reference

### Greek letters — lowercase

| Shortcut | Output | Name |
|---|---|---|
| `;alpha` | α | alpha |
| `;beta` | β | beta |
| `;gamma` | γ | gamma |
| `;delta` | δ | delta |
| `;epsilon` | ε | epsilon |
| `;zeta` | ζ | zeta |
| `;eta` | η | eta |
| `;theta` | θ | theta |
| `;iota` | ι | iota |
| `;kappa` | κ | kappa |
| `;lambda` | λ | lambda |
| `;mu` | μ | mu |
| `;nu` | ν | nu |
| `;xi` | ξ | xi |
| `;pi` | π | pi |
| `;rho` | ρ | rho |
| `;sigma` | σ | sigma |
| `;tau` | τ | tau |
| `;upsilon` | υ | upsilon |
| `;phi` | φ | phi |
| `;chi` | χ | chi |
| `;psi` | ψ | psi |
| `;omega` | ω | omega |

### Greek letters — uppercase

| Shortcut | Output | Name |
|---|---|---|
| `;Gamma` | Γ | Gamma |
| `;Delta` | Δ | Delta |
| `;Theta` | Θ | Theta |
| `;Lambda` | Λ | Lambda |
| `;Xi` | Ξ | Xi |
| `;Pi` | Π | Pi |
| `;Sigma` | Σ | Sigma |
| `;Upsilon` | Υ | Upsilon |
| `;Phi` | Φ | Phi |
| `;Psi` | Ψ | Psi |
| `;Omega` | Ω | Omega |

### Calculus & analysis

| Shortcut | Output | Description |
|---|---|---|
| `;partial` | ∂ | partial derivative |
| `;grad` | ∇ | gradient / nabla |
| `;int` | ∫ | integral |
| `;iint` | ∬ | double integral |
| `;oint` | ∮ | contour integral |
| `;inf` | ∞ | infinity |
| `;Lcal` | ℒ | script L (loss) |
| `;ell` | ℓ | script ell |
| `;Ocal` | 𝒪 | big-O notation |

### Linear algebra

| Shortcut | Output | Description |
|---|---|---|
| `;T` | ⊤ | transpose |
| `;perp` | ⊥ | perpendicular / orthogonal |
| `;otimes` | ⊗ | tensor / Kronecker product |
| `;odot` | ⊙ | Hadamard (elementwise) product |
| `;oplus` | ⊕ | direct sum |
| `;norm` | ‖ | norm brackets |
| `;langle` | ⟨ | left angle bracket |
| `;rangle` | ⟩ | right angle bracket |
| `;det` | det | determinant |
| `;tr` | tr | trace |
| `;rank` | rank | matrix rank |
| `;diag` | diag | diagonal matrix |
| `;vec` | vec | vectorization |

### Probability & statistics

| Shortcut | Output | Description |
|---|---|---|
| `;E` | 𝔼 | expectation |
| `;V` | 𝕍 | variance (blackboard) |
| `;P` | ℙ | probability measure |
| `;I` | 𝕀 | indicator function |
| `;sim` | ∼ | distributed as |
| `;nsim` | ≁ | not distributed as |
| `;propto` | ∝ | proportional to |
| `;indep` | ⊥⊥ | independent |
| `;Cov` | Cov | covariance |
| `;Var` | Var | variance |
| `;Std` | Std | standard deviation |
| `;KL` | KL(P‖Q) | KL divergence template |
| `;Normal` | 𝒩(μ,σ²) | normal distribution |
| `;Uniform` | 𝒰(a,b) | uniform distribution |
| `;Bern` | Bernoulli(p) | Bernoulli distribution |
| `;Cat` | Categorical(π) | categorical distribution |
| `;Dir` | Dirichlet(α) | Dirichlet distribution |

### Deep learning — activations & layers

| Shortcut | Output |
|---|---|
| `;sigmoid` | σ(x) = 1/(1+e⁻ˣ) |
| `;tanh` | tanh(x) |
| `;relu` | ReLU(x) = max(0,x) |
| `;lrelu` | LeakyReLU(x) = max(αx,x) |
| `;softmax` | softmax(xᵢ) = eˣⁱ / Σⱼ eˣʲ |
| `;layernorm` | LayerNorm(x) |
| `;batchnorm` | BatchNorm(x) |
| `;dropout` | Dropout(x, p) |

### Deep learning — loss functions

| Shortcut | Output |
|---|---|
| `;crossentropy` | ℒ = -Σᵢ yᵢ log(ŷᵢ) |
| `;mse` | ℒ = (1/n) Σᵢ (yᵢ - ŷᵢ)² |
| `;mae` | ℒ = (1/n) Σᵢ \|yᵢ - ŷᵢ\| |
| `;bce` | ℒ_BCE = -[y log(ŷ) + (1-y) log(1-ŷ)] |
| `;huber` | ℒ_huber |

### Deep learning — optimisation

| Shortcut | Output |
|---|---|
| `;sgd` | θ ← θ - η∇θℒ |
| `;adam1` | mₜ = β₁mₜ₋₁ + (1-β₁)gₜ |
| `;adam2` | vₜ = β₂vₜ₋₁ + (1-β₂)gₜ² |
| `;adamupdate` | θ ← θ - η m̂ₜ/(√v̂ₜ + ε) |
| `;argmin` | argmin |
| `;argmax` | argmax |
| `;dloss` | ∂ℒ/∂θ |

### Transformers & attention

| Shortcut | Output |
|---|---|
| `;attention` | Attention(Q,K,V) = softmax(QKᵀ/√dₖ)V |
| `;multihead` | MultiHead(Q,K,V) = Concat(head₁,...,headₕ)Wᴼ |
| `;ffn` | FFN(x) = max(0, xW₁+b₁)W₂+b₂ |
| `;posenc` | PE(pos,2i) = sin(pos/10000^(2i/dmodel)) |

### Reinforcement learning

| Shortcut | Output |
|---|---|
| `;valuefn` | V(s) = 𝔼[Σₜ γᵗ rₜ \| s₀=s] |
| `;qfn` | Q(s,a) |
| `;policy` | π(a\|s) |
| `;transition` | 𝒯(s'\|s,a) |
| `;discount` | γ |
| `;td` | δₜ = rₜ + γV(sₜ₊₁) - V(sₜ) |
| `;advantage` | Aᵠ(s,a) = Qᵠ(s,a) - Vᵠ(s) |

---

## Installation

### macOS (System-wide — recommended)

1. Download [`ml_math_shortcuts.plist`](./ml_math_shortcuts.plist)
2. Open **System Settings** → **Keyboard** → **Text Replacements**
3. Click the `···` button (bottom left) → **Import…**
4. Select the downloaded `.plist` file
5. Done — shortcuts work in every app that uses the macOS keyboard system

> Works in Notes, Pages, Notion (desktop), Slack, Messages, Mail, and most native apps. Does **not** work in web browsers (Chrome/Firefox) due to sandboxing — use the desktop app where available.

### Verify it's working

Open any text field (e.g. Notes), type `;alpha` followed by a space — it should replace with `α`.

---

## Contributing

Suggestions and additions are welcome! Please open an issue or pull request.

When adding new entries, follow the naming convention:
- `;name` (lowercase) for lowercase/symbol outputs
- `;Name` (capitalised) for uppercase Greek or named sets
- `;keyword` for full formula snippets

---

## License

MIT License — free to use, modify, and share.

---

## Author

**[Your Name]**  
[your-website.com](https://your-website.com) · [Twitter/X](https://x.com/yourhandle) · [LinkedIn](https://linkedin.com/in/yourprofile)

If this saved you time, consider giving the repo a ⭐
