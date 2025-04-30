---
title: Optical chip enables hybrid neural network
summary: Combining optical chips with traditional electronic hardware, we have developed a hybrid neural network that can be used to directly detect the properties of photons. Hybrid neural networks demonstrate stronger robustness in photon purity estimation and can even estimate purity in the case of incomplete measurements.
#date: 2023-10-24
type: docs
math: false
tags:
  - optical chip
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

[Hugo Blox Builder](https://hugoblox.com) is designed to give technical content creators a seamless experience. You can focus on the content and the Hugo Blox Builder which this template is built upon handles the rest.

**Embed videos, podcasts, code, LaTeX math, and even test students!**

On this page, you'll find some examples of the types of technical content that can be rendered with Hugo Blox.

## Video

Teach your course by sharing videos with your students. Choose from one of the following approaches:

{{< youtube D2vj0WcvH5c >}}

**Youtube**:

    {{</* youtube w7Ft2ymGmfc */>}}

**Bilibili**:

    {{</* bilibili id="BV1WV4y1r7DF" */>}}

**Video file**

Videos may be added to a page by either placing them in your `assets/media/` media library or in your [page's folder](https://gohugo.io/content-management/page-bundles/), and then embedding them with the _video_ shortcode:

    {{</* video src="my_video.mp4" controls="yes" */>}}

## Podcast

You can add a podcast or music to a page by placing the MP3 file in the page's folder or the media library folder and then embedding the audio on your page with the _audio_ shortcode:

    {{</* audio src="ambient-piano.mp3" */>}}

Try it out:

{{< audio src="ambient-piano.mp3" >}}

## Test students

Provide a simple yet fun self-assessment by revealing the solutions to challenges with the `spoiler` shortcode:

```markdown
{{</* spoiler text="👉 Click to view the solution" */>}}
You found me!
{{</* /spoiler */>}}
```

renders as

{{< spoiler text="👉 Click to view the solution" >}} You found me 🎉 {{< /spoiler >}}

## Math

Hugo Blox Builder supports a Markdown extension for $\LaTeX$ math. You can enable this feature by toggling the `math` option in your `config/_default/params.yaml` file.

To render _inline_ or _block_ math, wrap your LaTeX math with `{{</* math */>}}$...${{</* /math */>}}` or `{{</* math */>}}$$...$${{</* /math */>}}`, respectively.

{{% callout note %}}
We wrap the LaTeX math in the Hugo Blox _math_ shortcode to prevent Hugo rendering our math as Markdown.
{{% /callout %}}

Example **math block**:

```latex
{{</* math */>}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{</* /math */>}}
```

renders as

{{< math >}}
$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$
{{< /math >}}

Example **inline math** `{{</* math */>}}$\nabla F(\mathbf{x}_{n})${{</* /math */>}}` renders as {{< math >}}$\nabla F(\mathbf{x}_{n})${{< /math >}}.

Example **multi-line math** using the math linebreak (`\\`):

```latex
{{</* math */>}}
$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
{{</* /math */>}}
```

renders as

{{< math >}}

$$
f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}
$$

{{< /math >}}

## Code

Hugo Blox Builder utilises Hugo's Markdown extension for highlighting code syntax. The code theme can be selected in the `config/_default/params.yaml` file.


    ```python
    import pandas as pd
    data = pd.read_csv("data.csv")
    data.head()
    ```

renders as

```python
import pandas as pd
data = pd.read_csv("data.csv")
data.head()
```

## Inline Images

```go
{{</* icon name="python" */>}} Python
```

renders as

{{< icon name="python" >}} Python

## Did you find this page helpful? Consider sharing it 🙌


Combining optical chips with traditional electronic hardware, we have developed a hybrid neural network that can be used to directly detect the properties of photons. Hybrid neural networks demonstrate stronger robustness in photon purity estimation and can even estimate purity in the case of incomplete measurements.



## 🧑🏻‍🔧️ Experimental platform

The optical chip can be controlled by changing phase of light in each path, which is realized by adjusting voltage on the electrode patches. I have designed and set up the platform including voltage-control system, temperature-control module and light-coupling system.
{{< figure src="chip.jpg" caption="Experimental platform for optical chip" alt="screen reader text" width="100%" >}}

## 💻 Hybrid neural network

The hybrid quantum-classical neural network has following advantages:
- Self-adaptive
- Avoid theoretical calculation of post process
- Robust against static noise

{{< figure src="ONN.jpg" caption="Concept of hybrid quantum-classical neural network
with optical chip. (a) General neural network architecture composed of an unitary transformation and classical neural network layers including active functions. (b) Unitary evolution on the input light with interferometers on a optical chip. The output is transferred to electron signals by light detectors." alt="screen reader text" width="100%" >}}


## 📈 Hybrid NN enhances robustness

Hybrid NN is robust against phase noise and detection noise.

{{< figure src="3.jpg" caption="Performance of hybrid NN in purity estimation of qudit state with complete measurements" alt="screen reader text" width="100%" >}}

## 📈 Estimating properties with incomplete information

When information about the property is incomplete, hybrid network still offers close estimations of property, and adapt itself to achieve higher accuracy when the unknown states are constrained in some form, while traditional algorithms (LI and PLS) could not work.

{{< figure src="4.jpg" caption="Performance of hybrid NN in purity estimation of qudit state with incomplete measurements" alt="screen reader text" width="100%" >}}