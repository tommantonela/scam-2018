# Towards Anticipation of Architectural Smells using  Link Prediction Techniques
Repository corresponding to the SCAM paper "Towards Anticipation of Architectural Smells using  Link Prediction Techniques". 
Available at https://arxiv.org/abs/1808.06362

Software systems naturally evolve, and this evolution often brings design problems that cause system degradation. Architectural smells are typical symptoms of such problems, and several of these smells are related to undesired dependencies among modules. The early detection of these smells is important for developers, because they can plan ahead for maintenance or refactoring efforts, thus preventing system degradation. Existing tools for identifying architectural smells can detect the smells once they exist in the source code. This means that their undesired dependencies are already created. In this work, we explore a forward-looking approach that is able to infer groups of likely module dependencies that can anticipate architectural smells in a future system version. Our approach considers the current module structure as a network, along with information from previous versions, and applies link prediction techniques (from the field of social network analysis). In particular, we focus on dependency-related smells, such as Cyclic Dependency and Hublike Dependency, which fit well with the link prediction model. An initial evaluation with two open-source projects shows that, under certain considerations, the predictions of our approach are satisfactory. Furthermore, the approach can be extended to other types of dependency-based smells or metrics.

This repository presents the reproducibility kit corresponding to the two software systems used for performing the experimental evaluation: SubscriberDB and Apache Derby.

For each system, it is available:

* Source code
* .jar file
* Dependency graphs in format *.odem
* Process Content-based similarities

.odem files were created using [CDA (Class Dependency Analyzer)](http://www.dependency-analyzer.org/)
