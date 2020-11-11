<script>
    let disabled;
    let values = {
        name: "",
        address: "",
        email: "",
        status: "",
        jobs: "",
        organization: "",
        photoUrl: "",
        logoUrl: "",
        backgroundUrl: "",
    }
    const inputData = {
        name: {
            label: "name",
            type: "text",
            placeholder: "Enter name here"
        },
        address: {
            label: "address",
            type: "text",
            placeholder: "Enter address here"
        },
        email: {
            label: "name",
            type: "email",
            placeholder: "Enter email here"
        },
        status: {
            label: "status",
            type: "text",
            placeholder: "Enter your status here...."
        },
        job: {
            label: "job",
            type: "text",
            placeholder: "Enter profession here"
        },
        organization: {
            label: "organization",
            type: "text",
            placeholder: "Enter your organization"
        },
    }
    function resetForm() {
        disabled = true
        values = {
            name: "",
            address: "",
            email: "",
            status: "",
            jobs: "",
            organization: "",
            photoUrl: "",
            logoUrl: "",
            backgroundUrl: "",
        }

    }
    function onSubmit() {

    }
</script>
<form>
    <div class="form-group">
        <label class="label">Name</label>
        <input type="text" class="form-control" placeholder="Name">
    </div>
    <div class="form-group">
        <label class="label">address</label>
        <input type="text" class="form-control" placeholder="Enter address">
    </div>
    <div class="form-group">
        <label class="label">email</label>
        <input type="text" class="form-control" placeholder="Name">
    </div>
    <div class="form-group">
        <label>Status</label>
        <input type="text" class="form-control" placeholder="Status">
    </div>
    <div class="form-group">
        <label>Job</label>
        <input type="text" class="form-control" placeholder="Job">
    </div>
    <div class="form-group">
        <label>Organization</label>
        <input type="text" class="form-control" placeholder="Enter your organization">
    </div>
</form>
