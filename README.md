# demand_experiment
Hidden Demand Model


!git clone -q https://github.com/ds4e/demand_experiment.git
%cd /content/demand_experiment

from demand import demand

responses = demand(price=14.0)
print(len(responses), responses.sum())
