# tensor-network-project-5-solved
**TO GET THIS SOLUTION VISIT:** [Tensor network Project 5 Solved](https://www.ankitcodinghub.com/product/tensor-network-machine-learning-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126145&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Tensor network Project 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Tensor network algorithms extend beyond quantum many-body physics and find applications in various machine learning tasks. You can use tensor networks for directly solving the machine learning task, as datasets classification [1], or for compressing the size of a traditional machine learning model [2]. When used to solve a machine learning task, they are better than traditional machine learning models in a specific domain: explainability. Tensor networks do not display non-linearities, and are thus much easier to understand.

In this project, you will analyze the performances of a matrix product state (MPS) ansatz to classify the MNIST dataset. You will use the MPS class in quantum_tea_leaves, and specifically, employ the optimization algorithm from Ref. [1]. The idea of the algorithm is sketched below. A feature map $Phi(x)$ is applied to the input data. Then, the decision function is constructed and the weights are optimized via a sweeping algorithm similar to DMRG.

{width=”800px”}

Tasks:

1. Successfully classify the digits $3$ and $8$ of the MNIST dataset using the MPS classifier. Encode the dataset mapping each pixel in a qubit with state: math |q angle = sqrt{1-p_i}ket{0} + p_i ket{1}, where $|p_i|^2$ is the (normalized) intensity of the pixel. We call this method MPS1. What are the performances?

2. Successfully classify the digits $3$ and $8$ of the MNIST dataset using the MPS classifier. Encode the dataset in a statevector form, such

as: math |psi angle = sum_i p_i ket{i}, where $|p_i|^2$ is the (normalized) intensity of the pixel. We call this method MPS2. What are the performances?

3. By analyzing the entanglement entropy of the MPS classifier, are you able to understand which are the important characteristics of your system? Which of the two encodings is better for explainabilities? Does it become easier if you instead try to classify $0$ and $1$? How does the entanglement entropy and the accuracy vary with the bond dimension?

4. [Optional] Solve the same problem with your favorite neural network. Following Ref. [2] compress the weights of the neural network.

Which method is better memory-wise? MPS1, MPS2, NN, or MPS-compressed NN?
