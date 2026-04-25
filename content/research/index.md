---
title: "Research & Publications"
# ensure it's visible
#menu: "main"
hidemeta: true
showAuthor: false
showComments: false
---
<style>
    /* 1. Hide the default PaperMod cover image */
    .cover {
        display: none !important;
    }

    /* 2. Create the full-width banner area */
    .post-header {
        margin: 0 !important;
        width: 100vw;
        position: relative;
        left: 50%;
        right: 50%;
        margin-left: -50vw !important;
        margin-right: -50vw !important;
        
        /* Set your image here */
        background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), 
                    url('background1.jpg') no-repeat center center;
        background-size: cover;
        
        height: 400px; /* Reduced height as requested */
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        color: white; /* Title color on the image */
    }

    /* 3. Style the Title specifically */
    .post-header .post-title {
        color: #ffffff;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.8); /* Makes text pop against image */
        margin: 0;
    }

    /* 4. Keep the actual research list centered and normal width */
    .post-content {
        max-width: var(--main-width);
        margin: 40px auto;
        padding: 0 var(--gap);
    }
</style>

### Current Research:

My primary research at **BITS-Pilani, Goa** involves studying synchronization of neuronal networks. I work with reduced neuron models (simplified versions of neuron models). I am interested in adapting more and more realistic scenarios that mimic the actual biological settings, even in these seemingly abstract models.

|  |  |
| :--- | :--- |
| <img src="/images/neuron.jpg" width="1500" height="200" alt="Structure of a biological neuron showing axons and dendrites"> | Neurons are the buildig blocks of the nervous system. The human brain contains tens of billions of neurons, and each can be connected to thousands of other neurons through channels called synapses. |

There are models such as [Hogkin-Huxley model](https://doi.org/10.1113/jphysiol.1952.sp004764), that models the complex dynamics of these neurons with great detail. But, this model consists of four nonlinear, coupled, first-order differential equations to describe the dynamics of a single neuron. Thus, when modelling large networks of neurons, relative simpler reduced models are used to model the dynamics of individual neurons of the network.

The network topology with which these neurons are connected in a given neuronal networks play an instrumental role in the dynamics observed as well. 

---

### Publications

**1. Explosive synchronization in networks of Type-I neurons with electrical synapses** **Akshay S. Harish** and Gaurav Dar.
*Chaos 36, 033147 (2026).*
[View on arXiv](https://arxiv.org/abs/2512.03600) | [View DOI](https://doi.org/10.1063/5.0314833)

**2. Self-integrating dual oxide memristor for artificial neuron functionality** B. Manoj Kumar, **Akshay S. Harish**, C. Malavika, Gaurav Dar, and E. S. Kannan.  
*APL Electronic Devices 1, 026102* (2025).  
[View DOI](https://doi.org/10.1063/5.0253472)
