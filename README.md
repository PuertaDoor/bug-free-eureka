# bug-free-eureka
Implementation of a paper : Zero-shot Query Contextualization for Conversational Search (https://arxiv.org/abs/2204.10613)

To collect 2019, 2020 and 2021 docs, type ./data_collector.sh (you need to contact the NIST to get the WaPo dataset)

Make sure you have datamaestro and experimaestro-ir in your repo :


git clone https://github.com/experimaestro/datamaestro.git

pip install -e datamaestro

git clone https://github.com/experimaestro/experimaestro-ir.git

pip install -e experimaestro-ir
