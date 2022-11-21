<script>
export default {
    name: "AppContacts"
}
</script>

<template>
    <section class="ms_contacts py-5">
        <div class="ms_container">
            <div class="row align-items-center">
                <div class="col-8">
                    <div class="ms_heading">
                        <h4>about the network</h4>
                        <h2>The Company</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur a repellat quaerat asperiores minus totam beatae.</p>
                    </div>
                    <div class="ms_form-contacts">
                        <div class="row g-3">
                            <div class="col-md">
                                <div class="form-floating">
                                    <input type="name" class="form-control" id="floatingNameForm" placeholder="name@example.com">
                                    <label for="floatingNameForm">Name</label>
                                </div>
                            </div>
                            <div class="col-md">
                                <div class="form-floating">
                                    <input type="email" class="form-control" id="floatingEmailForm" placeholder="name@example.com">
                                    <label for="floatingEmailForm">Email address</label>
                                </div>
                            </div>
                        </div>
                        <div class="row g-3 py-3">
                            <div class="col-md">
                                <div class="form-floating">
                                    <input type="number" class="form-control" id="floatingNumberForm" placeholder="321 4567890" >
                                    <label for="floatingNumberForm">Phone</label>
                                </div>
                            </div>
                            <div class="col-md">
                                <div class="form-floating">
                                    <select class="form-select" id="floatingSelectForm">
                                        <option selected>More Info</option>
                                        <option value="1">One</option>
                                        <option value="2">Two</option>
                                        <option value="3">Three</option>
                                    </select>
                                    <label for="floatingSelectForm">More Info</label>
                                </div>
                            </div>
                        </div>
                            
                        <div class="form-floating">
                            <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
                            <label for="floatingTextarea2">Comments</label>
                        </div>
                        <div class="col-12">
                            <button type="submit" class="ms_btn ms_main-btn my-3">Subscribe</button>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    icons
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.ms_contacts {
    width: 100%;
}
</style>