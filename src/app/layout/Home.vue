<template>
    <div id="page-top">
        <!-- Header -->
        <Header></Header>

        <!-- Sections -->
        <div class="page-section-wrapper">
            <!-- Masthead -->
            <header class="masthead">
                <div class="container">
                    <div class="masthead-subheading">Welcome To Our Studio!</div>
                    <div class="masthead-heading text-uppercase">It's Nice To Meet You</div>
                    <a class="btn btn-primary btn-xl text-uppercase" href="#services">Tell Me More</a>
                </div>
            </header>
            <!-- Services -->
            <section class="page-section" id="services">
                <div class="container">
                    <div class="text-center">
                        <h2 class="section-heading text-uppercase">Services</h2>
                        <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
                    </div>
                    <div class="row text-center">
                        <div class="col-md-4">
                            <span class="fa-stack fa-4x">
                                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                                <i class="fas fa-shopping-cart fa-stack-1x fa-inverse"></i>
                            </span>
                            <h4 class="my-3">E-Commerce</h4>
                            <p class="text-muted">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto
                                quo inventore harum ex magni, dicta impedit.
                            </p>
                        </div>
                        <div class="col-md-4">
                            <span class="fa-stack fa-4x">
                                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                                <i class="fas fa-laptop fa-stack-1x fa-inverse"></i>
                            </span>
                            <h4 class="my-3">Responsive Design</h4>
                            <p class="text-muted">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto
                                quo inventore harum ex magni, dicta impedit.
                            </p>
                        </div>
                        <div class="col-md-4">
                            <span class="fa-stack fa-4x">
                                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
                            </span>
                            <h4 class="my-3">Web Security</h4>
                            <p class="text-muted">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima maxime quam architecto
                                quo inventore harum ex magni, dicta impedit.
                            </p>
                        </div>
                    </div>
                </div>
            </section>
            <!-- Portfolio Grid -->
            <SectionPortfolio></SectionPortfolio>
            <!-- About -->
            <section class="page-section" id="about">
                <div class="container">
                    <div class="text-center">
                        <h2 class="section-heading text-uppercase">About</h2>
                        <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
                    </div>
                    <ul class="timeline">
                        <li>
                            <div class="timeline-image">
                                <img class="rounded-circle img-fluid" src="@assets/images/about/1.jpeg" alt="..." />
                            </div>
                            <div class="timeline-panel">
                                <div class="timeline-heading">
                                    <h4>2009-2011</h4>
                                    <h4 class="subheading">Our Humble Beginnings</h4>
                                </div>
                                <div class="timeline-body">
                                    <p class="text-muted">
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt ut voluptatum
                                        eius sapiente, totam reiciendis temporibus qui quibusdam, recusandae sit vero
                                        unde, sed, incidunt et ea quo dolore laudantium consectetur!
                                    </p>
                                </div>
                            </div>
                        </li>
                        <li class="timeline-inverted">
                            <div class="timeline-image">
                                <img class="rounded-circle img-fluid" src="@assets/images/about/2.jpeg" alt="..." />
                            </div>
                            <div class="timeline-panel">
                                <div class="timeline-heading">
                                    <h4>March 2011</h4>
                                    <h4 class="subheading">An Agency is Born</h4>
                                </div>
                                <div class="timeline-body">
                                    <p class="text-muted">
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt ut voluptatum
                                        eius sapiente, totam reiciendis temporibus qui quibusdam, recusandae sit vero
                                        unde, sed, incidunt et ea quo dolore laudantium consectetur!
                                    </p>
                                </div>
                            </div>
                        </li>
                        <li>
                            <div class="timeline-image">
                                <img class="rounded-circle img-fluid" src="@assets/images/about/3.jpeg" alt="..." />
                            </div>
                            <div class="timeline-panel">
                                <div class="timeline-heading">
                                    <h4>December 2015</h4>
                                    <h4 class="subheading">Transition to Full Service</h4>
                                </div>
                                <div class="timeline-body">
                                    <p class="text-muted">
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt ut voluptatum
                                        eius sapiente, totam reiciendis temporibus qui quibusdam, recusandae sit vero
                                        unde, sed, incidunt et ea quo dolore laudantium consectetur!
                                    </p>
                                </div>
                            </div>
                        </li>
                        <li class="timeline-inverted">
                            <div class="timeline-image">
                                <img class="rounded-circle img-fluid" src="@assets/images/about/4.jpeg" alt="..." />
                            </div>
                            <div class="timeline-panel">
                                <div class="timeline-heading">
                                    <h4>July 2020</h4>
                                    <h4 class="subheading">Phase Two Expansion</h4>
                                </div>
                                <div class="timeline-body">
                                    <p class="text-muted">
                                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sunt ut voluptatum
                                        eius sapiente, totam reiciendis temporibus qui quibusdam, recusandae sit vero
                                        unde, sed, incidunt et ea quo dolore laudantium consectetur!
                                    </p>
                                </div>
                            </div>
                        </li>
                        <li class="timeline-inverted">
                            <div class="timeline-image">
                                <h4>
                                    Be Part
                                    <br />
                                    Of Our
                                    <br />
                                    Story!
                                </h4>
                            </div>
                        </li>
                    </ul>
                </div>
            </section>
            <!-- Team -->
            <section class="page-section bg-light" id="team">
                <div class="container">
                    <div class="text-center">
                        <h2 class="section-heading text-uppercase">Our Amazing Team</h2>
                        <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
                    </div>
                    <div class="row">
                        <div class="col-lg-4">
                            <div class="team-member">
                                <img class="mx-auto rounded-circle" src="@assets/images/team/1.jpeg" alt="..." />
                                <h4>Parveen Anand</h4>
                                <p class="text-muted">Lead Designer</p>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Parveen Anand Twitter Profile"
                                    ><i class="fab fa-twitter"></i
                                ></a>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Parveen Anand Facebook Profile"
                                    ><i class="fab fa-facebook-f"></i
                                ></a>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Parveen Anand LinkedIn Profile"
                                    ><i class="fab fa-linkedin-in"></i
                                ></a>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <div class="team-member">
                                <img class="mx-auto rounded-circle" src="@assets/images/team/2.jpeg" alt="..." />
                                <h4>Diana Petersen</h4>
                                <p class="text-muted">Lead Marketer</p>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Diana Petersen Twitter Profile"
                                    ><i class="fab fa-twitter"></i
                                ></a>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Diana Petersen Facebook Profile"
                                    ><i class="fab fa-facebook-f"></i
                                ></a>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Diana Petersen LinkedIn Profile"
                                    ><i class="fab fa-linkedin-in"></i
                                ></a>
                            </div>
                        </div>
                        <div class="col-lg-4">
                            <div class="team-member">
                                <img class="mx-auto rounded-circle" src="@assets/images/team/3.jpeg" alt="..." />
                                <h4>Larry Parker</h4>
                                <p class="text-muted">Lead Developer</p>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Larry Parker Twitter Profile"
                                    ><i class="fab fa-twitter"></i
                                ></a>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Larry Parker Facebook Profile"
                                    ><i class="fab fa-facebook-f"></i
                                ></a>
                                <a
                                    class="btn btn-dark btn-social mx-2"
                                    href="#!"
                                    aria-label="Larry Parker LinkedIn Profile"
                                    ><i class="fab fa-linkedin-in"></i
                                ></a>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-8 mx-auto text-center">
                            <p class="large text-muted">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut eaque, laboriosam
                                veritatis, quos non quis ad perspiciatis, totam corporis ea, alias ut unde.
                            </p>
                        </div>
                    </div>
                </div>
            </section>
            <!-- Clients -->
            <div class="py-5">
                <div class="container">
                    <div class="row align-items-center">
                        <div class="col-md-3 col-sm-6 my-3">
                            <a href="#!"
                                ><img
                                    class="img-fluid img-brand d-block mx-auto"
                                    src="@assets/images/logos/microsoft.svg"
                                    alt="..."
                                    aria-label="Microsoft Logo"
                            /></a>
                        </div>
                        <div class="col-md-3 col-sm-6 my-3">
                            <a href="#!"
                                ><img
                                    class="img-fluid img-brand d-block mx-auto"
                                    src="@assets/images/logos/google.svg"
                                    alt="..."
                                    aria-label="Google Logo"
                            /></a>
                        </div>
                        <div class="col-md-3 col-sm-6 my-3">
                            <a href="#!"
                                ><img
                                    class="img-fluid img-brand d-block mx-auto"
                                    src="@assets/images/logos/facebook.svg"
                                    alt="..."
                                    aria-label="Facebook Logo"
                            /></a>
                        </div>
                        <div class="col-md-3 col-sm-6 my-3">
                            <a href="#!"
                                ><img
                                    class="img-fluid img-brand d-block mx-auto"
                                    src="@assets/images/logos/ibm.svg"
                                    alt="..."
                                    aria-label="IBM Logo"
                            /></a>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Contact -->
            <section class="page-section" id="contact">
                <div class="container">
                    <div class="text-center">
                        <h2 class="section-heading text-uppercase">Contact Us</h2>
                        <h3 class="section-subheading text-muted">Lorem ipsum dolor sit amet consectetur.</h3>
                    </div>
                    
                    <form id="contactForm" data-sb-form-api-token="API_TOKEN">
                        <div class="row align-items-stretch mb-5">
                            <div class="col-md-6">
                                <div class="form-group">
                                    <!-- Name input-->
                                    <input
                                        class="form-control"
                                        id="name"
                                        type="text"
                                        placeholder="Your Name *"
                                        data-sb-validations="required"
                                    />
                                    <div class="invalid-feedback" data-sb-feedback="name:required">
                                        A name is required.
                                    </div>
                                </div>
                                <div class="form-group">
                                    <!-- Email address input-->
                                    <input
                                        class="form-control"
                                        id="email"
                                        type="email"
                                        placeholder="Your Email *"
                                        data-sb-validations="required,email"
                                    />
                                    <div class="invalid-feedback" data-sb-feedback="email:required">
                                        An email is required.
                                    </div>
                                    <div class="invalid-feedback" data-sb-feedback="email:email">
                                        Email is not valid.
                                    </div>
                                </div>
                                <div class="form-group mb-md-0">
                                    <!-- Phone number input-->
                                    <input
                                        class="form-control"
                                        id="phone"
                                        type="tel"
                                        placeholder="Your Phone *"
                                        data-sb-validations="required"
                                    />
                                    <div class="invalid-feedback" data-sb-feedback="phone:required">
                                        A phone number is required.
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <div class="form-group form-group-textarea mb-md-0">
                                    <!-- Message input-->
                                    <textarea
                                        class="form-control"
                                        id="message"
                                        placeholder="Your Message *"
                                        data-sb-validations="required"
                                    ></textarea>
                                    <div class="invalid-feedback" data-sb-feedback="message:required">
                                        A message is required.
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- Submit success message-->
                        <!---->
                        <!-- This is what your users will see when the form-->
                        <!-- has successfully submitted-->
                        <div class="d-none" id="submitSuccessMessage">
                            <div class="text-center text-white mb-3">
                                <div class="fw-bolder">Form submission successful!</div>
                                To activate this form, sign up at
                                <br />
                                <a href="https://startbootstrap.com/solution/contact-forms"
                                    >https://startbootstrap.com/solution/contact-forms</a
                                >
                            </div>
                        </div>
                        
                        <div class="d-none" id="submitErrorMessage">
                            <div class="text-center text-danger mb-3">Error sending message!</div>
                        </div>
                        <!-- Submit Button-->
                        <div class="text-center">
                            <button
                                class="btn btn-primary btn-xl text-uppercase disabled"
                                id="submitButton"
                                type="submit"
                            >
                                Send Message
                            </button>
                        </div>
                    </form>
                </div>
            </section>
            <!-- Example -->
            <!-- <ArticleList :contentType="'banner'" v-slot="{ loading, results }">
                <div v-if="loading" class="skeleton skeleton-banner"></div>
                <div v-else>
                    <Banner :banner="results" />
                </div>
            </ArticleList> -->
        </div>

        <!-- Footer-->
        <Footer></Footer>
    </div>
</template>

<script>
console.log("AppLayout loaded");

import { defineComponent } from "vue";
import SectionPortfolio from "@src/app/modules/SectionPortfolio.vue";
import Header from "@layout/Header.vue";
import Footer from "@layout/Footer.vue";
import ArticleList from "@components/ArticleList.vue";

export default defineComponent({
    name: "AppLayout",
    components: {
        Header,
        SectionPortfolio,
        Footer,
        ArticleList
    }
});
</script>

<style lang="css"></style>
