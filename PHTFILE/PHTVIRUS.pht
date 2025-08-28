def get_pht_icd10_code(description):
    """
    Returns ICD-10 code for Pulmonary Hypertension based on description.
    """
    description = description.lower()

    if "primary" in description or "idiopathic" in description:
        return "I27.0 – Primary pulmonary hypertension"
    elif "arterial" in description or "group 1" in description:
        return "I27.21 – Pulmonary arterial hypertension"
    elif "left heart" in description or "group 2" in description:
        return "I27.22 – PH due to left heart disease"
    elif "lung disease" in description or "hypoxia" in description or "group 3" in description:
        return "I27.23 – PH due to lung diseases or hypoxia"
    elif "thromboembolic" in description or "group 4" in description:
        return "I27.24 – Chronic thromboembolic PH"
    elif "multifactorial" in description or "group 5" in description:
        return "I27.29 – Other secondary pulmonary hypertension"
    else:
        return "Unknown – Please provide more specific description"

# Example usage:
print(get_pht_icd10_code("Group 3 pulmonary hypertension due to COPD"))
