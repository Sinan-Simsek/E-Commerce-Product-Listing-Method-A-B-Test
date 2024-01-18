# E-Commerce-Product-Listing-Method-A-B-Test

#####################################################
# Comparison of AB Testing and Existing and New Product Listing Pages
#####################################################

#####################################################
# Problem
#####################################################

# An e-commerce site has conducted a test study for the new product 
# listing page it has designed, and both control and test data have been shared.



#####################################################
# Dataset
#####################################################

# # control ve test dataset: 37 observation, 4 variable
# Date: Website Entry Date
# Pageviews: # of pageviews
# Clicks: # of clicks
# Payments: Total Payment



#####################################################
# Project Duties
#####################################################

######################################################
# AB Testing (Two Independent Samples T Test)
######################################################

# 1. Create Hyphothesis
# 2. Hyphothesis Control
#   - 1. Normality Distribution Hyphothesis (shapiro)
#   - 2. Variance Homogeneity (levene)
# 3. Application of Hyphothesis
#   - 1. If both hyphothesis are satisfied, two independent samples T-Test is applied
#   - 2. If not satisfied, mannwhitneyu test is applied
# 4. Comment based on p-value
