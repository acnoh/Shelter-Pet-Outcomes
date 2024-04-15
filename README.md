# Shelter-Pet-Outcomes
### Exploring pet outcomes of City of Long Beach Animal Shelter from years 2017-2024
**Intro:** Exploring shelter pet outcomes to determine if there are any significant trends in the outcomes of cats and dogs.
**Data/Operation Abstraction Design:** This dataset was downloaded from [data.longbeach.gov](https://data.longbeach.gov/explore/dataset/animal-shelter-intakes-and-outcomes/information/?flg=en-us&disjunctive.animal_type&disjunctive.primary_color&disjunctive.sex&disjunctive.intake_cond&disjunctive.intake_type&disjunctive.reason&disjunctive.outcome_type&disjunctive.outcome_subtype&disjunctive.intake_is_dead&disjunctive.outcome_is_dead).
It contained several null values that were dropped. The "Sex" column was also split into two new columns, "gender" and "spay/neuter." It contained several other types of pets that were not used in this analysis as their quantities were much lower than cats and dogs.  
  **Future Work:** The plan for future work is to focus the analysis solely on adoption and euthanasia outcomes to determine if there are any interesting trends among those outcomes.  
  
