<script lang="ts">

    // define props
    export let name = '';
    export let email = '';
    export let subject = '';
    export let comment =  '';

    // methods decalarations
    const trimContent = (comment) => {
        if (comment.length > 100) {
           return `${comment.substring(0, 100)}...`
        }
        return comment
    }
    const setName = (event) => {
        name = event.target.value;
    }
</script>


<div class="row">
    <div class="col-md-6">
        <div class="mb-3">
            <label class="form-label" for='name'>
                Your Name <span class="text-danger">*</span>
            </label>
            <input
                name="name"
                class="form-control"
                type="text"
                value={name}
                on:input={setName}
            />
        </div>
    </div>

    <div class="col-md-6">
        <div class="mb-3">
            <label class="form-label" for='email'>
                Your Email <span class="text-danger">*</span>
            </label>
            <input
                name="email"
                class="form-control"
                type="email"
                value={email}
            />
        </div>
    </div>

    <div class="col-12">
        <div class="mb-3">
            <label class="form-label" for='subject'>
                Subject
            </label>
            <input
                name="subject"
                class="form-control"
                value={subject}
            />
        </div>
    </div>

    <div class="col-12">
        <div class="mb-3">
            <label class="form-label" for='comment'>
                Comments <span class="text-danger">*</span>
            </label>
            <textarea
                name="comment" rows="4"
                value={comment} class="form-control"
            />
        </div>
    </div>
</div>
