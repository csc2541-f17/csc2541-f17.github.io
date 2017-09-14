---
id: calendar
name: Calendar
heading: Calendar
subheading: Calendar&#58;
image: ""
---



<table>
    <tr>
        <th>
        </th>
        <th>
            Topic
        </th>
        <th>
            Readings
        </th>
    </tr>
    <tr>
        <td>
            9/15
        </td>
        <td>
            Overview
        </td>
        <td>
            Overview
            <ul>
                <li><a href="http://www.nature.com/nature/journal/v521/n7553/full/nature14541.html">Ghahramani, 2015. Probabilistic machine learning and artificial intelligence.</a></li>
            </ul>
            Bayesian regression
            <ul>
                <li><a href="http://authors.library.caltech.edu/13792/1/MACnc92a.pdf">MacKay, 1992. Bayesian interpolation.</a></li>
                <li><a href="http://mlg.eng.cam.ac.uk/zoubin/papers/occam.pdf">Rasmussen and Ghahramani, 2001. Occam's razor.</a> </li>
                <li>Review: <a href="https://metacademy.org/graphs/concepts/bayesian_parameter_estimation">Bayesian parameter estimation</a>, <a href="https://metacademy.org/graphs/concepts/bayesian_linear_regression">Bayesian linear regression</a></li>
            </ul>
            Calibration
            <ul>
                <li><a href="https://arxiv.org/abs/1706.04599">Guo et al., 2017. On calibration of modern neural networks.</a></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            9/22
        </td>
        <td>
            Gaussian Processes
        </td>
        <td>
            Foundations
            <ul>
            <li><a href="http://www.gaussianprocess.org/gpml/chapters/">GPML, Chapter 2</a></li>
            </ul>
            Structured kernels
            <ul>
                <li><a href="http://www.gaussianprocess.org/gpml/chapters/">skim GPML sections 4.1-4.2</a></li>
                <li><a href="http://www.gaussianprocess.org/gpml/chapters/">GPML, Chapter 5</a></li>
                <li><a href="https://www.cs.toronto.edu/~duvenaud/cookbook/index.html">David Duvenaud's kernel cookbook</a></li>
                <li><a href="http://proceedings.mlr.press/v28/wilson13.pdf">Wilson and Adams, 2013. Gaussian process kernels for pattern discovery and extrapolation</a></li>
                <li><a href="http://proceedings.mlr.press/v28/duvenaud13.pdf">Duvenaud et al., 2013. Structure discovery in nonparametric regression through compositional kernel search</a></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            9/29
        </td>
        <td>
            Bayesian Neural Nets
        </td>
        <td>
            Background
            <ul>
                <li><a href="https://metacademy.org/graphs/concepts/backpropagation">backpropagation</a></li>
                <li><a href="https://metacademy.org/graphs/concepts/metropolis_hastings">Metropolis-Hastings</a></li>
            </ul>
            Foundations
            <ul>
                <li><a href="http://www.mitpressjournals.org/doi/abs/10.1162/neco.1992.4.3.448">MacKay, 1992. A practical Bayesian framework for backpropagation networks.</a></li>
                <li><a href="http://www.csri.utoronto.ca/~radford/ftp/thesis.pdf">Neal, 1995. Bayesian learning for neural networks.</a> Chapter 2.</li>
            </ul>
            Hamiltonian Monte Carlo
            <ul>
                <li><a href="https://arxiv.org/abs/1206.1901">Neal, 2012. MCMC using Hamiltonian dynamics.</a> (focus on sections 1-3)</li>
            </ul>
            Stochastic gradient Langevin dynamics
            <ul>
                <li><a href="http://machinelearning.wustl.edu/mlpapers/paper_files/ICML2011Welling_398.pdf">Welling and Teh, 2011. Bayesian learning via stochastic gradient Langevin dynamics.</a></li>
                <li><a href="http://papers.nips.cc/paper/5965-bayesian-dark-knowledge">Balan et al., 2015. Bayesian dark knowledge</a></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            10/6
        </td>
        <td>
            Variational Inference for BNNs
        </td>
        <td>
            Background
            <ul>
                <li><a href="https://en.wikipedia.org/wiki/Variational_Bayesian_methods">variational Bayes</a></li>
            </ul>
            Variational inference for BNNs
            <ul>
                <li><a href="http://dl.acm.org/citation.cfm?id=168306">Hinton and van Camp, 1993. Keeping the neural networks simple by minimizing the description length of the weights.</a></li>  
                <li><a href="http://papers.nips.cc/paper/4329-practical-variational-inference-for-neural-networks">Graves, 2011. Practical variational inference for neural networks</a></li>
                <li><a href="http://papers.nips.cc/paper/5666-variational-dropout-and-the-local-reparameterization-trick">Kingma, Salimans, and Welling, 2015. Variational dropout and the local reparameterization trick.</a></li>
                <li><a href="http://proceedings.mlr.press/v48/gal16.html">Gal and Ghahramani, 2016. Dropout as Bayesian approximation: representing model uncertainty in deep learning</a></li>
            </ul>
            Sparsification
            <ul>
                <li><a href="https://arxiv.org/abs/1705.08665">Louizos et al., 2017. Bayesian compression for deep learning.</a></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            10/12
        </td>
        <td>
            Project proposals due!
        </td>
        <td>
            Send by e-mail to csc2541-submit at cs dot toronto dot edu. Include "CSC2541 Project Proposal" in subject line.
        </td>
    </tr>
    <tr>
        <td>
            10/13
        </td>
        <td>
            Variational Inference for GPs
        </td>
        <td>
            <p>Note: this is among the most mathematically demanding sessions, and the rest of the course doesn't build much on it, so don't get bogged down in the details.</p>
            Natural gradient and stochastic variational inference
            <ul>
                <li>Natural gradient tutorial (coming soon!)</li>
                <li><a href="http://www.jmlr.org/papers/volume14/hoffman13a/hoffman13a.pdf">Hoffman, Blei, Wang, and Paisley, 2013. Stochastic variational inference</a></li>
                <li>Note: this material is included because it's used by Hensman et al., and also because natural gradient and SVI are just good things to know about.</li>
            </ul>
            Sparse GPs
            <ul>
                <li><a href="http://proceedings.mlr.press/v5/titsias09a/titsias09a.pdf">Titsias, 2009. Variational learning of inducing variables in sparse Gaussian processes</a></li>
                <li><a href="http://papers.nips.cc/paper/6477-understanding-probabilistic-sparse-gaussian-process-approximations">Bauer, van der Wilk, and Ghahramani, 2016. Understanding probabilistic sparse Gaussian process approximations.</a></li>
                <li><a href="https://arxiv.org/abs/1309.6835">Hensman, Fusi, and Lawrence, 2013. Gaussian processes for big data.</a></li>
            </ul>
            Variational inference and generalization
            <ul>
                <li><a href="http://www.jmlr.org/papers/volume3/seeger02a/seeger02a.pdf">Seeger, 2002. PAC-Bayesian generalization error bounds for Gaussian process classification</a> (Section 3 can be skimmed)</li> 
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            10/20
        </td>
        <td>
            Exploration I: Active Learning and Bandits
        </td>
        <td>
            Active Learning
            <ul>
                <li><a href="http://www.mitpressjournals.org/doi/abs/10.1162/neco.1992.4.4.590">MacKay, 1992. Information-based objective functions for active data selection.</a></li>
                <li><a href="https://arxiv.org/abs/1704.03003">Graves et al., 2017. Automated curriculum learning for neural networks.</a></li>
            </ul>
            Bandits
            <ul>
               <li><a href="http://people.eecs.berkeley.edu/~pabbeel/cs287-fa09/readings/Auer+al-UCB.pdf">Auer et al., 2002. Finite-time analysis of the multiarmed bandit problem.</a></li>
               <li><a href="http://papersdb.cs.ualberta.ca/~papersdb/uploaded_files/633/paper_ecml06.pdf">Kocsis and Szepesvari, 2006. Bandit based Monte-Carlo planning.</a></li>
               <li><a href="https://arxiv.org/abs/1707.02038">Russo et al., 2017. A tutorial on Thompson sampling.</a></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            10/27
        </td>
        <td>
            Exploration II: Bayesian Optimization
        </td>
        <td>
            Bayesian optimization
            <ul>
                <li><a href="http://papers.nips.cc/paper/4522-practical-bayesian-optimization-of-machine-l">Snoek, Larochelle, and Adams, 2012. Practical Bayesian optimization of machine learning algorithms.</a></li>
                <li><a href="https://arxiv.org/abs/0912.3995">Srinivas et al., 2010. Gaussian process optimization in the bandit setting: no regret and experimental design.</a></li>
                <li><a href="https://arxiv.org/abs/1502.05700">Snoek et al., 2015. Scalable Bayesian optimization using deep neural networks.</a></li>
            </ul>
            Exploiting structure
            <ul>
                <li><a href="http://papers.nips.cc/paper/5086-multi-task-bayesian-optimization">Swersky, Snoek, and Adams, 2013. Multi-task Bayesian optimization</a></li>
                <li><a href="https://arxiv.org/abs/1406.3896">Swersky, Snoek, and Adams, 2014. Freeze-thaw Bayesian optimization</a></li>
                <li><a href="http://www.cs.toronto.edu/~rgrosse/aistats2017-additive.pdf">Gardner et al., 2017. Discovering and exploiting additive structure for Bayesian optimization.</a></li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            11/3
        </td>
        <td>
            Exploration III: Reinforcement Learning
        </td>
        <td>
            Model-free
            <ul>
                <li><a href="http://papers.nips.cc/paper/6500-deep-exploration-via-bootstrapped-dqn">Osband et al., 2016. Deep exploration via bootstrapped DQN.</a></li>
                <li>TBD</li>
            </ul>
            Model-based
            <ul>
                <li><a href="http://machinelearning.wustl.edu/mlpapers/paper_files/ICML2011Deisenroth_323.pdf">Deisenroth and Rasmussen, 2011. PILCO: a model-based and data-efficient approach to policy search</a></li>
                <li><a href="https://arxiv.org/abs/1605.07127">Depeweg et al., 2016. Learning and policy search in stochastic dynamical systems with Bayesian neural networks</a></li>
                <li>TBD</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            11/10
        </td>
        <td>
            Adversarial Robustness
        </td>
        <td>
            Basic phenomena
            <ul>
                <li><a href="https://arxiv.org/abs/1412.6572">Goodfellow, Shlens, and Szegedy, 2014. Explaining and harnessing adversarial examples.</a></li>
                <li><a href="https://arxiv.org/abs/1701.00160">Ian Goodfellow's NIPS tutorial</a></li>
                <li><a href="https://arxiv.org/abs/1602.02697">Papernot et al., 2016. Practical black-box attacks against machine learning systems using adversarial examples</a></li>
                <li><a href="https://arxiv.org/abs/1702.06832">Kos, Fischer, and Song, 2017. Adversarial examples for generative models</a></li>
            </ul>
            Attacks and defenses
            <ul>
                <li><a href="https://arxiv.org/abs/1511.07528">Papernot et al., 2015. The limitations of deep learning in adversarial settings</a></li>
                <li><a href="https://arxiv.org/abs/1707.02476">Bradshaw, Matthews, and Ghahramani, 2017. Adversarial Examples, Uncertainty, and Transfer Testing Robustness in Gaussian Process Hybrid Deep Networks</a></li>
                <li>TBD</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td>
            11/17
        </td>
        <td>
            TBD
        </td>
        <td>
        </td>
    </tr>
    <tr>
        <td>
            11/24 and 12/1
        </td>
        <td>
            Project Presentations
        </td>
        <td>
        </td>
        </tr>
    <tr>
        <td>
            12/10
        </td>
        <td>
            Project reports due
        </td>
        <td>
            Send by e-mail to csc2541-submit at cs dot toronto dot edu. Include "CSC2541 Final Report" in subject line.
        </td>
    </tr>
</table>




