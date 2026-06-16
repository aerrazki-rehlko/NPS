# NPS

dashboard-v2 : 

    - Fixed the Target threshold line visualisation (removed label redundancy)
    - Modified the + and - icons with arrows on the assignment groups change period comparison
    - Centralised data in a json format array (see the model below)

    const NPS_FEEDBACK_DATA = [
    {
        "instance_id": "FB000001",
        "caller_department": "Corporate IT",
        "assigned_to": "Ines Martin",
        "assigned_to_department": "Service Desk",
        "assigned_to_assignment_group": "Major Incident Desk",
        "updated_at": "2025-09-01T17:19:00Z",
        "nps_score": 10
    },
    {
        "instance_id": "FB000002",
        "caller_department": "Research & Development",
        "assigned_to": "Nadia Lopez",
        "assigned_to_department": "Cybersecurity",
        "assigned_to_assignment_group": "Security Operations",
        "updated_at": "2025-09-01T17:19:00Z",
        "nps_score": 9
    }]