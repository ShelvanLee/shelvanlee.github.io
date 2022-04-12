				<section class="panel spotlight (size modifier) (orientation modifier)">
					<div class="content (span modifier)">
						(content)
					</div>
					<div class="image (image modifiers)" data-position="(image position modifier)">
						<img src="(image URL)" alt="" />
					</div>
				</section>

			Modifiers

				Orientation

					left           Content on the left.
					right          Content on the right.

				Image

					filtered       Applies a gradient filter to the image.
					tinted         Applies a tint filter to the image.

				Image Position (required)

					top left       Position image in the top-left corner.
					top            Position image along the top edge.
					top right      Position image in the top-right corner.
					right          Position image along the right edge.
					bottom right   Position image in the bottom-right corner.
					bottom         Position image along the bottom edge.
					bottom left    Position image in the bottom-left corner.
					left           Position image along the left edge.
					center         Position image in the center.

			Example

				<section class="panel spotlight large right">
					<div class="content">
						<h1>Spotlight</h1>
						<p>Lorem ipsum dolor sit amet.</p>
					</div>
					<div class="image" data-position="center">
						<img src="/path/to/image.jpg" alt="" />
					</div>
				</section>


		Gallery
		-------

			A lightbox-enabled gallery.

			HTML

				<div class="gallery">
					<a href="(full image URL)" class="image (image modifiers) (span modifier)" data-position="(image position modifier)">
						<img src="(thumbnail image URL)" alt="" />
					</a>
					<a href="(full image URL)" class="image (image modifiers) (span modifier)" data-position="(image position modifier)">
						<img src="(thumbnail image URL)" alt="" />
					</a>
					<a href="(full image URL)" class="image (image modifiers) (span modifier)" data-position="(image position modifier)">
						<img src="(thumbnail image URL)" alt="" />
					</a>
					<div class="group (span modifier)">
						<a href="(full image URL)" class="image (image modifiers) (span modifier)" data-position="(image position modifier)">
							<img src="(thumbnail image URL)" alt="" />
						</a>
						<a href="(full image URL)" class="image (image modifiers) (span modifier)" data-position="(image position modifier)">
							<img src="(thumbnail image URL)" alt="" />
						</a>
						<a href="(full image URL)" class="image (image modifiers) (span modifier)" data-position="(image position modifier)">
							<img src="(thumbnail image URL)" alt="" />
						</a>
						<a href="(full image URL)" class="image (image modifiers) (span modifier)" data-position="(image position modifier)">
							<img src="(thumbnail image URL)" alt="" />
						</a>
						...
					</div>
					...
				</div>

				Note: The "group" element creates a dual-row group of images. Images inside this group will
				automatically wrap to the next row when they exceed its width (as defined by its span modifier).
				You can have as many groups in a gallery as you like.

			Modifiers

				Image

					filtered       Applies a gradient filter to the image.
					tinted         Applies a tint filter to the image.

				Image Position (required)

					top left       Position image in the top-left corner.
					top            Position image along the top edge.
					top right      Position image in the top-right corner.
					right          Position image along the right edge.
					bottom right   Position image in the bottom-right corner.
					bottom         Position image along the bottom edge.
					bottom left    Position image in the bottom-left corner.
					left           Position image along the left edge.
					center         Position image in the center.

			Example

				<div class="gallery">
					<a href="/images/thumbnails/01.jpg" class="image filtered span-2" data-position="center">
						<img src="/images/fulls/01.jpg" alt="" />
					</a>
					<a href="/images/thumbnails/02.jpg" class="image filtered span-4" data-position="center">
						<img src="/images/fulls/02.jpg" alt="" />
					</a>
					<div class="group span-4">
						<a href="/images/thumbnails/03.jpg" class="image filtered span-2" data-position="center">
							<img src="/images/fulls/03.jpg" alt="" />
						</a>
						<a href="/images/thumbnails/04.jpg" class="image filtered span-2" data-position="center">
							<img src="/images/fulls/04.jpg" alt="" />
						</a>
						<a href="/images/thumbnails/05.jpg" class="image filtered span-2" data-position="center">
							<img src="/images/fulls/05.jpg" alt="" />
						</a>
						<a href="/images/thumbnails/06.jpg" class="image filtered span-2" data-position="center">
							<img src="/images/fulls/06.jpg" alt="" />
						</a>
					</div>
				</div>
