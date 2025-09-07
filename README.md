# StudyPlannerbody {
        background-color: #f5f7fb;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    
    .navbar {
        background: linear-gradient(135deg, var(--primary), var(--secondary));
    }
    
    .sidebar {
        background-color: white;
        border-radius: 10px;
        box-shadow: 0 0 15px rgba(0,0,0,0.1);
        height: calc(100vh - 100px);
        position: sticky;
        top: 20px;
    }
    
    .main-content {
        background-color: white;
        border-radius: 10px;
        box-shadow: 0 0 15px rgba(0,0,0,0.1);
        padding: 25px;
    }
    
    .subject-badge {
        display: inline-block;
        width: 15px;
        height: 15px;
        border-radius: 50%;
        margin-right: 8px;
    }
    
    .calendar-day {
        border: 1px solid #dee2e6;
        height: 120px;
        padding: 8px;
        overflow-y: auto;
    }
    
    .calendar-day.current-day {
        background-color: rgba(67, 97, 238, 0.1);
        border: 2px solid var(--primary);
    }
    
    .session-event {
        font-size: 0.8rem;
        padding: 2px 5px;
        margin-bottom: 3px;
        border-radius: 3px;
        color: white;
    }
    
    .task-item {
        border-left: 4px solid;
        margin-bottom: 10px;
    }
    
    .stats-card {
        border-radius: 10px;
        background: linear-gradient(135deg, var(--primary), var(--secondary));
        color: white;
        padding: 20px;
        margin-bottom: 20px;
    }
</style>
